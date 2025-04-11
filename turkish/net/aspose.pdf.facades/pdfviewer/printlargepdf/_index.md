---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer yöntemi. Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.
type: docs
weight: 350
url: /tr/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(string filePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //print the file with adjusted size
iewer.AutoRotate = true;     //print the file with adjusted rotation
iewer.PrintPageDialog=false; //do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf");
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.Close()
```

### Ayrıca Bakınız

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

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

### Ayrıca Bakınız

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

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

### Ayrıca Bakınız

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

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

### Ayrıca Bakınız

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |
| pageSettings | PageSettings | Sayfa ayarları. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

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

### Ayrıca Bakınız

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Belirtilen sayfa ayarları ve yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasına sahipse veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı. |
| pageSettings | PageSettings | Sayfa ayarları. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

## Açıklamalar

Bu yöntem dosyanın açılmasını ve yazdırılmasını entegre eder ve BindPdf() yöntemini açıkça çağırmanıza gerek yoktur.

## Örnekler

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

### Ayrıca Bakınız

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)