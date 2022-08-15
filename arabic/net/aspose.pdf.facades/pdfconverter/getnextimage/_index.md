---
title: GetNextImage
second_title: Aspose.PDF لمرجع .NET API
description: يحفظ الصورة في ملف بتنسيق الصورة الافتراضي - jpeg.
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

يحفظ الصورة في ملف بتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

يحفظ الصورة في ملف بحجم الصفحة المحدد وتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

يحفظ الصورة في ملف بتنسيق صورة givin .

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

يحفظ الصورة في ملف بحجم الصفحة وتنسيق الصورة المحددين.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |
| format | ImageFormat | شكل الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

يحفظ الصورة للتدفق بتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

يحفظ الصورة للتدفق بحجم الصفحة المحدد.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

يحفظ الصورة للتدفق باستخدام تنسيق الصورة المحدد.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

يحفظ الصورة للتدفق بحجم الصفحة المحدد.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |
| format | ImageFormat | شكل الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

يحفظ الصورة في ملف بتنسيق وأبعاد وجودة الصورة المحددة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

يحفظ الصورة للتدفق باستخدام تنسيق صورة givin والأبعاد والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

يحفظ الصورة في ملف بتنسيق صورة givin وحجمها وجودتها.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Double | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Double | ارتفاع الصورة الوحدة بالبكسل .. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

يحفظ الصورة للدفق بتنسيق صورة givin وحجمها وجودتها.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Double | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Double | ارتفاع الصورة ، الوحدة بالبكسل. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

يحفظ الصورة في ملف بتنسيق وأبعاد الصورة المحددة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

يحفظ الصورة للدفق بتنسيق صورة givin وحجمها وجودتها.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

يحفظ الصورة للتدفق باستخدام تنسيق وجودة صورة محددين.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

يحفظ الصورة للتدفق مع تحديد حجم الصفحة وتنسيق الصورة والجودة.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |
| format | ImageFormat | شكل الصورة. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

يحفظ الصورة في ملف بتنسيق وجودة معينين للصورة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| format | ImageFormat | شكل الصورة. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

يحفظ الصورة في ملف بحجم الصفحة وتنسيق الصورة وجودتها.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ الصورة. |
| pageSize | PageSize | حجم صفحة الصورة. |
| format | ImageFormat | شكل الصورة. |
| quality | Int32 | جودة ملف Jpeg (0 ~ 100) ، 0 هي الأدنى و 100 هي الأعلى |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
