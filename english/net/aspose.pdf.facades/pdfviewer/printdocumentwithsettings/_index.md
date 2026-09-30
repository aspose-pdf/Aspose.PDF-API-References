---
title: "PdfViewer.PrintDocumentWithSettings"
linktitle: "PrintDocumentWithSettings"
articleTitle: "PrintDocumentWithSettings"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Prints the Pdf document with settings. If the document page size does not correspond to the printer paper size, set the AutoResize property..."
type: docs
weight: 210
url: "/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/"
product_version: "26.9.0"
---
## PrintDocumentWithSettings([PageSettings](../../../aspose.pdf.printing/pagesettings/), [PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printdocumentwithsettings}

Prints the Pdf document with settings. If the document page size does not correspond to the printer paper size,
 set the `AutoResize` property to determine whether a page will be extended/shrunk to fit the paper size.

printerSettings object is used to print the document.
 pageSettings.PrinterSettings object is ignored.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageSettings | PageSettings | The page setting of the printing document. |
| printerSettings | PrinterSettings | The printer setting of the printing document. |

## Examples

printerSettings object is used to print the document.
 pageSettings.PrinterSettings object is ignored.

```csharp
 [C#]
PdfViewer viewer = new PdfViewer();
viewer.BindPdf(@"d:\test.pdf");
viewer.AutoResize = true;         //print the file with adjusted size
viewer.AutoRotate = true;         //print the file with adjusted rotation
viewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
Aspose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
PrintDocument prtdoc = new PrintDocument();
ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
Aspose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
pgs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
pgs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

[VisualBasic]
Dim viewer As New PdfViewer()
viewer.BindPdf(@"d:\test.pdf")
viewer.AutoResize = True            'print the file with adjusted size
viewer.AutoRotate = True            'print the file with adjusted rotation
viewer.PrintPageDialog = False      'do not produce the page number dialog when printing
Dim ps As New Aspose.Pdf.Printing.PrinterSettings()
Dim prtdoc As New PrintDocument()
ps.PrinterName = prtdoc.PrinterSettings.PrinterName
Dim pgs As New Aspose.Pdf.Printing.PageSettings()
pgs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
pgs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
viewer.PrintDocumentWithSettings(pgs, ps)
viewer.Close()
```

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings([PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printdocumentwithsettings_1}

Prints the Pdf document with printer settings. Printer page settings (paper size, margins, and so on) will be set to default values
 for the selected printer.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | The printer setting of the printing document. |

## Examples

```csharp
 [C#]
PdfViewer viewer = new PdfViewer();
viewer.OpenPdfFile(@"d:\test.pdf");
viewer.AutoResize = true;         //print the file with adjusted size
viewer.AutoRotate = true;         //print the file with adjusted rotation
viewer.PrintPageDialog=false;//do not produce the page number dialog when printing
System.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
PrintDocument prtdoc = new PrintDocument();
ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
viewer.PrintDocumentWithSettings(ps);
viewer.ClosePdfFile();

[VisualBasic]
Dim viewer As PdfViewer = new PdfViewer()
viewer.OpenPdfFile(@"d:\test.pdf")
viewer.AutoResize = true;        'print the file with adjusted size
viewer.AutoRotate = true;        'print the file with adjusted rotation
viewer.PrintPageDialog=false;//do not produce the page number dialog when printing
Dim ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
Dim prtdoc As PrintDocument = new PrintDocument()
ps.PrinterName = prtdoc.PrinterSettings.PrinterName
viewer.PrintDocumentWithSettings(ps);
viewer.ClosePdfFile()
```

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

