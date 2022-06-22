---
title: GetNextImage
second_title: Aspose.PDF for .NET API 参考
description: 以默认图像格式 - jpeg 将图像保存到文件中
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

以默认图像格式 - jpeg 将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

将图像保存到具有给定页面大小和默认图像格式 - jpeg 的文件中。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

以 givin 图像格式将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| format | ImageFormat | 图像的格式。 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

将图像保存到具有给定页面大小和图像格式的文件中。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |
| format | ImageFormat | 图像的格式。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

使用默认图像格式 - jpeg 将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

将图像保存到给定页面大小的流中。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

以给定的图像格式将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| format | ImageFormat | 图像的格式。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

将图像保存到给定页面大小的流中。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| format | ImageFormat | 图像的格式。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

以给定的图像格式、尺寸和质量将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

以 givin 图像格式、尺寸和质量将图像保存到流。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

以 givin 图像格式、图像大小和质量将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Double | 图像宽度，单位是像素。 |
| imageHeight | Double | 图片高度，单位是像素.. |
| quality | Int32 | Jpeg文件的质量(0~100), 0 最低, 100 最高 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

以 givin 图像格式、大小和质量将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Double | 图像宽度，单位是像素。 |
| imageHeight | Double | 图像高度，单位是像素。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

以给定的图像格式和尺寸将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

以 givin 图像格式、大小和质量将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| format | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

以给定的图像格式和质量将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| format | ImageFormat | 图像的格式。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

以给定的页面大小、图像格式和质量将图像保存到流中。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| format | ImageFormat | 图像的格式。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

以给定的图像格式和质量将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| format | ImageFormat | 图像的格式。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

以给定的页面大小、图像格式和质量将图像保存到文件中。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |
| format | ImageFormat | 图像的格式。 |
| quality | Int32 | Jpeg文件的质量（0~100），0最低，100最高 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
