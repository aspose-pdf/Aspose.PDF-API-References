---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。检查 PDF 文档中是否还有可访问的图像。注意，必须先调用 ExtractImage 才能使用此方法"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

检查 PDF 文档中是否还有可访问的图像。注意：在使用此方法之前必须先调用 ExtractImage。

```csharp
public bool HasNextImage()
```

### 返回值

如果还有可访问的图像则返回 true

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


