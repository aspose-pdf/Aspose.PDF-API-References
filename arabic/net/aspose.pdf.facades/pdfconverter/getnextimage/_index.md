---
title: "PdfConverter.GetNextImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfConverter. تحفظ الصورة إلى ملف بصيغة الصورة الافتراضية jpeg"
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

يحفظ الصورة إلى ملف بصيغة الصورة الافتراضية - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

يحفظ الصورة إلى ملف بحجم صفحة محدد وصيغة الصورة الافتراضية - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

يحفظ الصورة إلى ملف بصيغة صورة محددة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |

## أمثلة

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

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

يحفظ الصورة إلى ملف باستخدام حجم الصفحة المحدد وتنسيق الصورة.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

يحفظ الصورة إلى تدفق بصيغة الصورة الافتراضية - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

يحفظ الصورة إلى تدفق بحجم صفحة محدد.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

يحفظ الصورة إلى تدفق بصيغة صورة محددة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

يحفظ الصورة إلى تدفق بحجم صفحة محدد.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد، الأبعاد والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

## أمثلة

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

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الأبعاد والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المعطى، حجم الصورة، والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Double | عرض الصورة، الوحدة هي pixels. |
| imageHeight | Double | ارتفاع الصورة، الوحدة هي pixels.. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

## أمثلة

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

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الحجم والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Double | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Double | ارتفاع الصورة، الوحدة هي pixel. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد والأبعاد.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

## أمثلة

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

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الحجم والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق البيانات لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

يحفظ الصورة إلى ملف باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف والاسم لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هي الأدنى و 100 هي الأعلى |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


