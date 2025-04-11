---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 属性。获取或设置将在其页面范围内执行提取操作的起始页面
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage 属性

获取或设置将在其页面范围内执行提取操作的起始页面。

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

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)