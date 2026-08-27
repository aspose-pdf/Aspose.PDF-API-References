---
title: "PdfConverter.GetNextImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfConverter 方法。将图像保存为文件，默认图像格式为 jpeg"
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

将图像保存到文件，使用默认图像格式 - jpeg。

```csharp
public void GetNextImage(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

将图像保存到文件，使用第 ith 给定的页面尺寸和默认图像格式 - jpeg。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

将图像保存到文件，使用给定的图像格式。

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| 格式 | ImageFormat | 图像的格式。 |

## 示例

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

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

将图像保存到文件，使用指定的页面尺寸和图像格式。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |
| 格式 | ImageFormat | 图像的格式。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

将图像保存到流，使用默认图像格式 - jpeg。

```csharp
public void GetNextImage(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

将图像保存到流，使用指定的页面尺寸。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

将图像保存到流，使用指定的图像格式。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| 格式 | ImageFormat | 图像的格式。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

将图像保存到流，使用指定的页面尺寸。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| 格式 | ImageFormat | 图像的格式。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

将图像保存到文件，使用给定的图像格式、尺寸和质量。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

## 示例

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

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

将图像保存到流，使用给定的图像格式、尺寸和质量。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

将图像保存到文件，使用给定的图像格式、图像尺寸和质量。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Double | 图像宽度，单位为像素。 |
| imageHeight | Double | 图像高度，单位为像素.. |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

## 示例

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

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

将图像保存到流，使用给定的图像格式、尺寸和质量。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Double | 图像宽度，单位为像素。 |
| imageHeight | Double | 图像高度，单位为像素。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

将图像保存到文件，使用给定的图像格式和尺寸。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

## 示例

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

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

将图像保存到流，使用给定的图像格式、尺寸和质量。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| 格式 | ImageFormat | 图像的格式。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

将图像保存到流，使用指定的图像格式和质量。

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| 格式 | ImageFormat | 图像的格式。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

将图像保存到流，使用指定的页面尺寸、图像格式和质量。

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| 格式 | ImageFormat | 图像的格式。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

将图像保存到文件，使用指定的图像格式和质量。

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| 格式 | ImageFormat | 图像的格式。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

将图像保存到文件，使用指定的页面尺寸、图像格式和质量。

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存图像的文件路径和名称。 |
| pageSize | PageSize | 图像的页面大小。 |
| 格式 | ImageFormat | 图像的格式。 |
| quality | Int32 | JPEG 文件的质量 (0~100)，0 为最低，100 为最高。 |

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


