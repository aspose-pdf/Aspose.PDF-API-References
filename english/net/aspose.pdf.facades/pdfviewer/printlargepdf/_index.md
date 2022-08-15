---
title: PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB this method is recommended to get better performance.
type: docs
weight: 320
url: /net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //print the file with adjusted size
iewer.AutoRotate = true;     //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'print the file with adjusted size
iewer.AutoRotate = true      'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed.. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //print the file with adjusted size
iewer.AutoRotate = true;        //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'print the file with adjusted size
iewer.AutoRotate = true         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |
| printerSettings | PrinterSettings | The printer settings. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'print the file with adjusted size
iewer.AutoRotate = true        'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed.. |
| printerSettings | PrinterSettings | The printer settings. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'print the file with adjusted size
iewer.AutoRotate = true        'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |
| pageSettings | PageSettings | The page settings. |
| printerSettings | PrinterSettings | The printer settings. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'print the file with adjusted size
iewer.AutoRotate = true       'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |
| pageSettings | PageSettings | The page settings. |
| printerSettings | PrinterSettings | The printer settings. |

### Remarks

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'print the file with adjusted size
iewer.AutoRotate = true       'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../../pdfviewer)
* namespace [Aspose.Pdf.Facades](../../pdfviewer)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
