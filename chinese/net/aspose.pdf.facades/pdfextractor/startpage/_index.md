---
title: "PdfExtractor.StartPage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 属性。获取或设置将在其执行提取操作的页面范围的起始页。"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

获取或设置将在其范围内执行提取操作的起始页。

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


