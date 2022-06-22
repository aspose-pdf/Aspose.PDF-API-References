---
title: SaveAsTIFF
second_title: Aspose.PDF for .NET API 参考
description: 将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件。 |

### 例子

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 输出文件。 |
| compressionType | CompressionType | 压缩类型。 |

### 例子

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### 也可以看看

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| pageSize | PageSize | 图像的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| pageSize | PageSize | 图像的页面大小。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| compressionType | CompressionType | 压缩类型。 |

### 也可以看看

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 输出流。 |
| compressionType | CompressionType | 压缩类型。 |

### 也可以看看

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| compressionType | CompressionType | 压缩类型。 |

### 也可以看看

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

将 pdf 文档的每一页转换为带有图像的图像并将图像保存到单个 TIFF 文件中。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

将 pdf 文档的每一页转换为带有图像的图像并将图像保存到单个 TIFF 文件中。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 保存 TIFF 图像的文件名 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存 TIFF 图像的流。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 也可以看看

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
