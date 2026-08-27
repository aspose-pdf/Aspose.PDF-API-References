---
title: "PdfViewer.CustomPrint"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Evento PdfViewer. Si verifica prima dell'inizio della stampa e consente di fornire gestori di stampa personalizzati al posto di quello predefinito"
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

Si verifica prima dell'inizio della stampa e consente di fornire gestori di stampa personalizzati al posto di quello predefinito.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## Esempi

L'esempio dimostra come stampare da Aspose.PDF su sistemi Linux. Il codice seguente è principalmente rivolto alla stampa da Aspose.PDF su sistemi Linux. Gli utenti di sistemi Windows possono continuare a utilizzare l'implementazione di stampa predefinita di PdfViewer senza fornire un gestore CustomPrint.

### Prerequisites

1. Sul sistema del server di stampa CUPS dovrebbe essere installato e configurato:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. Una stampante può essere configurata usando l'interfaccia web di CUPS. Facoltativamente, è possibile utilizzare una stampante PDF virtuale:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. Se il tuo sistema client (dove è in esecuzione l'app abilitata per Aspose.PDF) è diverso dal server di stampa, devi installare ed eseguire CUPS anche lì:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Imposta un gestore di stampa personalizzato che costruisce un comando lp e lo esegue con bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Invia il documento alla stampante PDF virtuale installata con il pacchetto printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Il documento verrà stampato utilizzando il gestore di stampa fornito
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Gestore di stampa personalizzato
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Imposta il nome della stampante su cui stampare
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Imposta il numero di copie
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Imposta l'intervallo di pagine da stampare
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Imposta la dimensione della carta
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Imposta l'orientamento orizzontale se richiesto
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Imposta la risoluzione della stampante
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

    // Imposta la stampa fronte/retro se richiesta
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

    // Il nome del file da stampare
    sb.AppendFormat("-- {0} ", e.FileName);

    // Esegui il comando lp preparato con bash
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

// Imposta un gestore di stampa personalizzato che costruisce un file di lavoro ipptool e lo esegue con ipptool tramite bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Invia il documento alla stampante PDF virtuale installata con il pacchetto printer-driver-cups-pdf
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// Il documento verrà stampato utilizzando il gestore di stampa fornito
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Gestore di stampa personalizzato
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // Il nome del file da stampare
    command.AppendFormat("-f {0} ", e.FileName);

    // Imposta l'URI della stampante su cui stampare
    command.Append(e.PrinterSettings.PrinterUri);

    // Ottieni il nome del file temporaneo per il file di lavoro ipptool
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Imposta il nome del lavoro e il tipo del lavoro
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Imposta le impostazioni predefinite del lavoro
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Imposta il numero di copie
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Imposta la dimensione della carta
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET utilizza 1/100 di pollice per rappresentare le dimensioni della carta mentre IPP richiede 1/1000 di millimetro – è necessaria la conversione
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Imposta i margini
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

    // Crea il file di lavoro ipptool
    File.WriteAllText(jobFile, sb.ToString());

    // Passa il file di lavoro a ipptool
    command.AppendFormat(" {0}", jobFile);

    // Esegui il comando ipptool preparato con bash
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

    // Elimina il file di lavoro temporaneo dopo che il documento è stato stampato
    File.Delete(jobFile);
}
```

### Vedi anche

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


