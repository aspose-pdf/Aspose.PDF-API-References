---
title: "PdfViewer.CustomPrint"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Événement PdfViewer. Se produit avant le démarrage de l'impression et permet de fournir des gestionnaires d'impression personnalisés à la place de celui par défaut"
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

Se produit avant le démarrage de l'impression et permet de fournir des gestionnaires d'impression personnalisés au lieu de celui par défaut.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## Exemples

L'exemple montre comment imprimer depuis Aspose.PDF sur des systèmes Linux. Le code suivant est principalement destiné à l'impression depuis Aspose.PDF sur des systèmes Linux. Les utilisateurs de systèmes Windows peuvent continuer à utiliser l'implémentation d'impression par défaut de PdfViewer sans fournir de gestionnaire CustomPrint.

### Prerequisites

1. Sur le système du serveur d'impression, CUPS doit être installé et configuré :
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. Une imprimante peut être configurée à l'aide de l'interface web de CUPS. Optionnellement, vous pouvez utiliser une imprimante PDF virtuelle :
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. Si votre système client (où l'application activée Aspose.PDF s'exécute) est différent du serveur d'impression, vous devez également y installer et y exécuter CUPS :
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Définir un gestionnaire d'impression personnalisé qui construit une commande lp et l'exécute avec bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Envoyer le document à l'imprimante PDF virtuelle installée avec le paquet printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Le document sera imprimé en utilisant le gestionnaire d'impression fourni
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Gestionnaire d'impression personnalisé
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Définir le nom de l'imprimante sur laquelle imprimer
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Définir le nombre de copies
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Définir la plage de pages à imprimer
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Définir la taille du papier
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Définir l'orientation paysage si demandé
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Définir la résolution de l'imprimante
    switch (e.PageSettings.PrinterResolution.Kind)
    {
        case PrinterResolutionKind.High:
            sb.Append("-o print-quality=5 ");
            break;

        case PrinterResolutionKind.Medium:
            sb.Append("-o print-quality=4 ");
            break;

        case PrinterResolutionKind.Draft:
            sb.Append("-o print-quality=3 ");
            break;
    }

    // Définir l'impression recto verso si demandé
    switch (e.PrinterSettings.Duplex)
    {
        case Duplex.Simplex:
            sb.Append("-o sides=one-sided ");
            break;

        case Duplex.Vertical:
            sb.Append("-o sides=two-sided-short-edge ");
            break;

        case Duplex.Horizontal:
            sb.Append("-o sides=two-sided-long-edge ");
            break;
    }

    // Le nom du fichier à imprimer
    sb.AppendFormat("-- {0} ", e.FileName);

    // Exécuter la commande lp préparée avec bash
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", sb.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }
}
```

### How to print a document using the ipptool

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Définir un gestionnaire d'impression personnalisé qui crée un fichier de travail ipptool et exécute ipptool avec bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Envoyer le document à l'imprimante PDF virtuelle installée avec le paquet printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Le document sera imprimé en utilisant le gestionnaire d'impression fourni
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Gestionnaire d'impression personnalisé
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // Le nom du fichier à imprimer
    command.AppendFormat("-f {0} ", e.FileName);

    // Définir l'URI de l'imprimante sur laquelle imprimer
    command.Append(e.PrinterSettings.PrinterUri);

    // Obtenir le nom du fichier temporaire pour le fichier de travail ipptool
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Définir le nom du travail et le type du travail
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Définir les paramètres par défaut du travail
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Définir le nombre de copies
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Définir la taille du papier
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET utilise 1/100e de pouce pour représenter la taille du papier tandis que IPP nécessite 1/1000e de millimètre - une conversion est nécessaire
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Définir les marges
    if (pageSettings.Margins != null)
    {
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Top * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-bottom-margin {0}{1}", (int) (e.PageSettings.Margins.Bottom * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-left-margin {0}{1}", (int) (e.PageSettings.Margins.Left * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Right * 25.4),
            Environment.NewLine);
    }

    sb.AppendLine("    MEMBER keyword media-source \"main\"");
    sb.AppendLine("    MEMBER keyword media-type \"stationery\"");
    sb.AppendLine("  }");

    sb.AppendLine("  FILE $filename");
    sb.AppendLine("  STATUS successful-ok");
    sb.AppendLine("  STATUS successful-ok-ignored-or-substituted-attributes");
    sb.AppendLine("  EXPECT job-id");
    sb.AppendLine("  EXPECT job-uri");
    sb.AppendLine("}");

    // Créer le fichier de travail ipptool
    File.WriteAllText(jobFile, sb.ToString());

    // Passer le fichier de travail à ipptool
    command.AppendFormat(" {0}", jobFile);

    // Exécuter la commande ipptool préparée avec bash
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", command.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }

    // Supprimer le fichier de travail temporaire après l'impression du document
    File.Delete(jobFile);
}
```

### Voir aussi

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


