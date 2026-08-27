---
title: "PdfViewer.CustomPrint"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfViewer-händelse. Uppstår innan utskriften startar och möjliggör att tillhandahålla anpassade utskrifts-hanterare istället för standard."
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

Inträffar innan utskriften startar och möjliggör att tillhandahålla anpassade utskrifts‑hanterare istället för standard.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## Exempel

Exemplet visar hur man skriver ut från Aspose.PDF på Linux-system. Följande kod är främst avsedd för utskrift från Aspose.PDF på Linux-system. Användare av Windows-system kan fortsätta använda standard-PdfViewer-utskriftsimplementationen utan att tillhandahålla en CustomPrint-hanterare.

### Prerequisites

1. På utskriftsserverns system bör CUPS installeras och konfigureras:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. En skrivare kan ställas in via CUPS webbgränssnitt. Eventuellt kan du använda en virtuell PDF-skrivare:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. Om ditt klientsystem (där den Aspose.PDF-aktiverade appen körs) är annorlunda än utskriftsservern, måste du också installera och köra CUPS där:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Ställ in en anpassad utskrifts-hanterare som bygger ett lp-kommando och kör det med bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Skicka dokumentet till den virtuella PDF-skrivaren som installerats med paketet printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Dokumentet kommer att skrivas ut med den angivna utskrifts-hanteraren
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Anpassad utskrifts-hanterare
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Ange namnet på skrivaren att skriva ut till
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Ange antalet kopior
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Ange intervallet av sidor att skriva ut
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Ange pappersstorlek
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Ange liggande orientering om begärt
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Ange skrivarupplösning
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

    // Ange dubbelsidig utskrift om begärt
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

    // Namnet på filen som ska skrivas ut
    sb.AppendFormat("-- {0} ", e.FileName);

    // Kör det förberedda lp-kommandot med bash
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

// Ställ in en anpassad utskrifts‑hanterare som bygger en ipptool‑jobbfil och kör ipptool med bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Skicka dokumentet till den virtuella PDF-skrivaren som installerats med paketet printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Dokumentet kommer att skrivas ut med den angivna utskrifts-hanteraren
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Anpassad utskrifts-hanterare
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // Namnet på filen som ska skrivas ut
    command.AppendFormat("-f {0} ", e.FileName);

    // Ställ in URI:n för skrivaren att skriva ut på
    command.Append(e.PrinterSettings.PrinterUri);

    // Hämta det tillfälliga filnamnet för ipptool‑jobbfilen
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Ställ in jobbnamn och typ av jobbet
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Ställ in standardinställningar för jobbet
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Ställ in antal kopior
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Ange pappersstorlek
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET använder 1/100 tum för att representera pappersstorlek medan IPP kräver 1/1000 millimeter – konvertering behövs
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Ställ in marginaler
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

    // Skapa ipptool‑jobbfil
    File.WriteAllText(jobFile, sb.ToString());

    // Skicka jobbfilen till ipptool
    command.AppendFormat(" {0}", jobFile);

    // Kör det förberedda ipptool‑kommandot med bash
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

    // Ta bort den tillfälliga jobbfilen efter att dokumentet har skrivits ut
    File.Delete(jobFile);
}
```

### Se även

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


