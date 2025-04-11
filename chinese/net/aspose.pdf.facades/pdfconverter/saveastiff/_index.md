---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 方法。将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件。 |

## 示例

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

### 另请参阅

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 输出文件。 |
| compressionType | CompressionType | 压缩类型。 |

## 示例

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

### 另请参阅

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

### 另请参阅

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参阅

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| pageSize | PageSize | 图像的页面大小。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| compressionType | CompressionType | 压缩类型。 |

### 另请参阅

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |

### 另请参阅

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 输出流。 |
| compressionType | CompressionType | 压缩类型。 |

### 另请参阅

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参阅

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

### 另请参阅

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| compressionType | CompressionType | 压缩类型。 |

### 另请参阅

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件。

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 要保存 TIFF 图像的文件名 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 要保存 TIFF 图像的流。 |
| settings | TiffSettings | 定义 TIFF 参数的设置对象。 |
| converter | IIndexBitmapConverter | 外部转换器 |

### 另请参阅

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)