---
title: "PdfViewer.PrintLargePdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfViewer. تفتح وتطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل"
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

يفتح ويطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

يفتح ويطبع تدفق Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الذي سيُفتح ويُطبع. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

يفتح ويطبع ملف Pdf كبير باستخدام إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

يفتح ويطبع تدفق Pdf كبير باستخدام إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الذي سيُفتح ويُطبع. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

يفتح ويطبع ملف Pdf كبير باستخدام إعدادات Page وإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |
| pageSettings | PageSettings | إعدادات الصفحة. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

يفتح ويطبع تدفق Pdf كبير باستخدام إعدادات Page وإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf الذي سيُفتح ويُطبع. |
| pageSettings | PageSettings | إعدادات الصفحة. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

## ملاحظات

تدمج هذه الطريقة فتح وطباعة الملف ولا تحتاج إلى استدعاء BindPdf() صراحةً.

## أمثلة

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

### انظر أيضًا

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


