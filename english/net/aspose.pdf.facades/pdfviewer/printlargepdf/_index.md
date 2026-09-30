---
title: "PdfViewer.PrintLargePdf"
linktitle: "PrintLargePdf"
articleTitle: "PrintLargePdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended..."
type: docs
weight: 30
url: "/net/aspose.pdf.facades/pdfviewer/printlargepdf/"
product_version: "26.9.0"
---
## PrintLargePdf(string) {#printlargepdf}

Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is 
 more than 3 MB, this method is recommended to get better performance.

This method integrates the opening and the printing of the file and you don't need to 
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog=false; //do not produce the page number dialog when printing
 viewer.PrintLargePdf(@"d:\test.pdf");
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 viewer.PrintLargePdf(@"d:\test.pdf")
 viewer.Close()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf_1}

Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is 
 more than 3 MB, this method is recommended to get better performance.

This method integrates the opening and the printing of the file and you don't need to
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog=false; //do not produce the page number dialog when printing
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
 viewer.Close()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, [PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printlargepdf_2}

Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds 
 of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

This method integrates the opening and the printing of the file and you don't need to 
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |
| printerSettings | PrinterSettings | The printer settings. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog = false; //do not produce the page number dialog when printing
 Aspose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
 viewer.PrintLargePdf(@"d:\test.pdf",ps);
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 Dim ps As New Aspose.Pdf.Printing.PrinterSettings()
 Dim prtdoc As New PrintDocument()
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName
 viewer.PrintLargePdf(@"d:\test.pdf",ps)
 viewer.Close()
```

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, [PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printlargepdf_3}

Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds 
 of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

This method has integrates the opening and the printing of the file and you don't need to 
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |
| printerSettings | PrinterSettings | The printer settings. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog = false; //do not produce the page number dialog when printing
 Aspose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 Dim ps As New Aspose.Pdf.Printing.PrinterSettings()
 Dim prtdoc As New PrintDocument()
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
 viewer.Close()
```

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, [PageSettings](../../../aspose.pdf.printing/pagesettings/), [PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printlargepdf_4}

Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf 
 file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to 
 get better performance.

This method integrates the opening and the printing of the file and you don't need to
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of Pdf file. |
| pageSettings | PageSettings | The page settings. |
| printerSettings | PrinterSettings | The printer settings. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog = false; //do not produce the page number dialog when printing
 Aspose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
 Aspose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
 pgs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
 pgs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
 viewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 Dim ps As New Aspose.Pdf.Printing.PrinterSettings()
 Dim prtdoc As New PrintDocument()
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName
 Dim pgs As New Aspose.Pdf.Printing.PageSettings()
 pgs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
 pgs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
 viewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
 viewer.Close()
```

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, [PageSettings](../../../aspose.pdf.printing/pagesettings/), [PrinterSettings](../../../aspose.pdf.printing/printersettings/)) {#printlargepdf_5}

Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf 
 file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to 
 get better performance.

This method integrates the opening and the printing of the file and you don't need to
 call the BindPdf() explicitly.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |
| pageSettings | PageSettings | The page settings. |
| printerSettings | PrinterSettings | The printer settings. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog = false; //do not produce the page number dialog when printing
 Aspose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName;
 Aspose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
 pgs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
 pgs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 Dim ps As New Aspose.Pdf.Printing.PrinterSettings()
 Dim prtdoc As New PrintDocument()
 ps.PrinterName = prtdoc.PrinterSettings.PrinterName
 Dim pgs As New Aspose.Pdf.Printing.PageSettings()
 pgs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
 pgs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
 viewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
 viewer.Close()
```

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

