---
title: PdfViewer.PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfViewer. Stampa il documento Pdf con impostazioni. Se la dimensione del documento non corrisponde alla dimensione della pagina, verrà estesa per adattarsi alla dimensione della pagina
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Stampa il documento Pdf con impostazioni. Se la dimensione del documento non corrisponde alla dimensione della pagina, verrà estesa per adattarsi alla dimensione della pagina.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageSettings | PageSettings | L'impostazione della pagina del documento di stampa. |
| printerSettings | PrinterSettings | L'impostazione della stampante del documento di stampa. |

## Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintDocumentWithSettings(pgs, ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True            'print the file with adjusted size
iewer.AutoRotate = True            'print the file with adjusted rotation
iewer.PrintPageDialog = False      'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintDocumentWithSettings(pgs, ps)
iewer.Close()
```

L'oggetto printerSettings viene utilizzato per stampare il documento. L'oggetto pageSettings.PrinterSettings viene ignorato.

### Vedi Anche

* classe [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Stampa il documento Pdf con impostazioni della stampante. La dimensione della pagina di output si adatterà alla dimensione della prima pagina del documento.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| printerSettings | PrinterSettings | L'impostazione della stampante del documento di stampa. |

## Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;        'print the file with adjusted size
iewer.AutoRotate = true;        'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile()
```

### Vedi Anche

* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)