---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 属性。获取或设置提取操作将在其执行的页范围的结束页。"
type: docs
weight: 20
url: /zh/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

获取或设置将在其执行提取操作的页面范围的结束页。

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


