---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。从 PDF 文档中检索下一张图像。注意，必须先调用 ExtractImage 才能使用此方法"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须先调用 ExtractImage。

```csharp
public bool GetNextImage(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 存放图像的文件 |

### 返回值

如果图像成功提取则返回 true

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

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

检索 PDF 文档中的下一张图像并使用给定的图像格式。注意：在使用此方法之前必须先调用 ExtractImage。

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 存放图像的文件 |
| 格式 | ImageFormat | 图像的格式。 |

### 返回值

如果图像成功提取则返回 true

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

检索 PDF 文件中的下一张图像并使用给定的图像格式将其存入流中。

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像数据的流 |
| 格式 | ImageFormat | 图像的格式。 |

### 返回值

如果图像成功提取则返回 true。

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

检索 PDF 文件中的下一张图像并将其存入流中。

```csharp
public bool GetNextImage(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 保存图像数据的流 |

### 返回值

如果图像成功提取则返回 true。

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


