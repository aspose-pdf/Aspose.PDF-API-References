---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 属性。获取或设置提取操作将执行的页面范围中的结束页
type: docs
weight: 20
url: /zh/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage 属性

获取或设置提取操作将执行的页面范围中的结束页。

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

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)