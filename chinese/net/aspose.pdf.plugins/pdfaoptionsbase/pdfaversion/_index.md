---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase 属性。获取或设置用于验证或转换的 PDF/A 标准版本
type: docs
weight: 110
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion 属性

获取或设置用于验证或转换的 PDF/A 标准版本。

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### 属性值

PDF/A 标准的版本。这可以是 [`PdfAStandardVersion`](../../pdfastandardversion/) 枚举中的一个值。

## 备注

PDF/A 标准版本用于确定 PDF/A 验证和转换的合规性级别。如果版本设置为自动，系统将根据文档元数据自动确定适当的 PDF/A 标准版本进行验证。对于 PDF/A 转换过程，自动默认设置为 PDF/A-1b 标准版本。

### 另请参阅

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)