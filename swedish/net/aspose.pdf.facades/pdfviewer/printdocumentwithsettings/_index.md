---
title: PdfViewer.PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-metod. Skriver ut Pdf-dokumentet med inställningar. Om dokumentstorleken inte motsvarar sidstorleken kommer den att utvidgas för att passa sidstorleken
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Skriver ut Pdf-dokumentet med inställningar. Om dokumentstorleken inte motsvarar sidstorleken, kommer den att utvidgas för att passa sidstorleken.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageSettings | PageSettings | Sidinställningen för det utskrivna dokumentet. |
| printerSettings | PrinterSettings | Skrivarinställningen för det utskrivna dokumentet. |

## Exempel

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

printerSettings-objektet används för att skriva ut dokumentet. pageSettings.PrinterSettings-objektet ignoreras.

### Se Även

* klass [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Skriver ut Pdf-dokumentet med skrivarinställningar. Utskriftssidans storlek kommer att passa dokumentets första sidstorlek.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Skrivarinställningen för det utskrivna dokumentet. |

## Exempel

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

### Se Även

* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)