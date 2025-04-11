---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 方法。 从 PDF 文档中检索下一个图像。 注意：必须在使用此方法之前调用 ExtractImage
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

从 PDF 文档中检索下一个图像。 注意：必须在使用此方法之前调用 ExtractImage。

```csharp
public bool GetNextImage(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 存储图像的文件 |

### 返回值

如果图像成功提取，则返回 true

## 示例

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

使用给定的图像格式从 PDF 文档中检索下一个图像。 注意：必须在使用此方法之前调用 ExtractImage。

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 存储图像的文件 |
| format | ImageFormat | 图像的格式。 |

### 返回值

如果图像成功提取，则返回 true

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

从 PDF 文件中检索下一个图像，并将其存储到具有给定图像格式的流中。

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 将保存图像数据的流 |
| format | ImageFormat | 图像的格式。 |

### 返回值

如果图像成功提取，则返回 true。

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

从 PDF 文件中检索下一个图像，并将其存储到流中。

```csharp
public bool GetNextImage(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 将保存图像数据的流 |

### 返回值

如果图像成功提取，则返回 true。

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)