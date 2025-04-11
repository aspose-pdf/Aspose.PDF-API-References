---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfConverter. تحفظ الصورة في ملف بتنسيق الصورة الافتراضي - jpeg
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

تحفظ الصورة في ملف بتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

تحفظ الصورة في ملف بحجم الصفحة المعطى وتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

تحفظ الصورة في ملف بالتنسيق المعطى للصورة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
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

تحفظ الصورة في ملف بحجم الصفحة المعطى وتنسيق الصورة.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

تحفظ الصورة في دفق بتنسيق الصورة الافتراضي - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

تحفظ الصورة في دفق بحجم الصفحة المعطى.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

تحفظ الصورة في دفق بالتنسيق المعطى للصورة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

تحفظ الصورة في دفق بحجم الصفحة المعطى.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

تحفظ الصورة في ملف بالتنسيق المعطى للصورة، والأبعاد والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

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

تحفظ الصورة في دفق بالتنسيق المعطى للصورة، والأبعاد والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

تحفظ الصورة في ملف بالتنسيق المعطى للصورة، وحجم الصورة، والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Double | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Double | ارتفاع الصورة، الوحدة هي بكسل. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

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

تحفظ الصورة في دفق بالتنسيق المعطى للصورة، والحجم والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Double | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Double | ارتفاع الصورة، الوحدة هي بكسل. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

تحفظ الصورة في ملف بالتنسيق المعطى للصورة والأبعاد.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

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

تحفظ الصورة في دفق بالتنسيق المعطى للصورة، والحجم والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

تحفظ الصورة في دفق بالتنسيق المعطى للصورة والجودة.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

تحفظ الصورة في دفق بحجم الصفحة المعطى، وتنسيق الصورة والجودة.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

تحفظ الصورة في ملف بالتنسيق المعطى للصورة والجودة.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

تحفظ الصورة في ملف بحجم الصفحة المعطى، وتنسيق الصورة والجودة.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسم الملف لحفظ الصورة. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| format | ImageFormat | تنسيق الصورة. |
| quality | Int32 | جودة ملف Jpeg (0~100)، 0 هو الأدنى و100 هو الأعلى |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)