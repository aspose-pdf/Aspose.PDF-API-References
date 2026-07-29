---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。从 PDF 文件中提取图像。"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

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

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


