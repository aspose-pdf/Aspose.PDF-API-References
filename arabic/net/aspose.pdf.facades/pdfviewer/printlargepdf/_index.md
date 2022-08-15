---
title: PrintLargePdf
second_title: Aspose.PDF لمرجع .NET API
description: يفتح ويطبع ملف PDF كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت  يوصى بهذه الطريقة للحصول على أداء أفضل.
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

يفتح ويطبع ملف PDF كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;     // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true      'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

يفتح ويطبع تدفق PDF كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf ليتم فتحه وطباعته .. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;        // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true         'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

يفتح ويطبع ملف Pdf كبير بإعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات من الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;       // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true        'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

يفتح ويطبع تدفق Pdf كبير بإعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات من الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf ليتم فتحه وطباعته .. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;       // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true        'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

يفتح ويطبع ملف PDF كبير بإعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف Pdf يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكبر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف Pdf. |
| pageSettings | PageSettings | إعدادات الصفحة. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;       // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
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
iewer.AutoResize = true       'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true       'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

يفتح ويطبع تدفق Pdf كبير مع إعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف Pdf يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | دفق pdf ليتم فتحه وطباعته. |
| pageSettings | PageSettings | إعدادات الصفحة. |
| printerSettings | PrinterSettings | إعدادات الطابعة. |

### ملاحظات

لقد دمجت هذه الطريقة فتح الملف وطباعته ولا تحتاج إلى استدعاء OpenPdfFile () بشكل صريح.

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;       // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
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
iewer.AutoResize = true       'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true       'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
