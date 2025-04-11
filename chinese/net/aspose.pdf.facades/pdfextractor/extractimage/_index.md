---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 方法。 从 PDF 文件中提取图像
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage 方法

从 PDF 文件中提取图像。

```csharp
public void ExtractImage()
```

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