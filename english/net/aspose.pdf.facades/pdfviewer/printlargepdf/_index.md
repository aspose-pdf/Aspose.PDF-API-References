---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer method. Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB this method is recommended to get better performance
type: docs
weight: 330
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

## Remarks

This method integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
PdfViewer viewer = new PdfViewer();
viewer.AutoResize = true;     //print the file with adjusted size
viewer.AutoRotate = true;     //print the file with adjusted rotation
viewer.PrintPageDialog=false; //do not produce the page number dialog when printing
viewer.PrintLargePdf(@"d:\test.pdf");
viewer.Close();

[VisualBasic]
Dim viewer As New PdfViewer()
viewer.AutoResize = True       'print the file with adjusted size
viewer.AutoRotate = True       'print the file with adjusted rotation
viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
viewer.PrintLargePdf(@"d:\test.pdf")
viewer.Close()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |

## Remarks

This method integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //print the file with adjusted size
iewer.AutoRotate = true;        //print the file with adjusted rotation
iewer.PrintPageDialog=false;    //do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True         'print the file with adjusted size
iewer.AutoRotate = True         'print the file with adjusted rotation
iewer.PrintPageDialog = False   'do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.Close()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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

## Remarks

This method integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.Close()
```

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened and printed. |
| printerSettings | PrinterSettings | The printer settings. |

## Remarks

This method has integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.Close()
```

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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

## Remarks

This method integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.Close()
```

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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

## Remarks

This method integrates the opening and the printing of the file and you don't need to call the BindPdf() explicitly.

## Examples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.Close()
```

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


