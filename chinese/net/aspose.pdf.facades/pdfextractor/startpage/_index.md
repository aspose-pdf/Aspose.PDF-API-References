---
title: StartPage
second_title: Aspose.PDF for .NET API 参考
description: 获取或设置要执行提取操作的页范围内的起始页
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

获取或设置要执行提取操作的页范围内的起始页。

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

### 也可以看看

* class [PdfExtractor](../../pdfextractor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfextractor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->