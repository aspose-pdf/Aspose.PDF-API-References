---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 方法。检查 PDF 文档中是否可以访问更多图像。注意：在使用此方法之前必须调用 ExtractImage
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage 方法

检查 PDF 文档中是否可以访问更多图像。注意：在使用此方法之前必须调用 ExtractImage。

```csharp
public bool HasNextImage()
```

### 返回值

如果可以访问更多图像，则返回 true

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