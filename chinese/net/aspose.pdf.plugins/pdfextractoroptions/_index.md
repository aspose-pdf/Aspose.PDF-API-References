---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractorOptions class. 表示 TextExtractor 和 ImageExtractor 插件的选项
type: docs
weight: 9070
url: /zh/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions class

表示 TextExtractor 和 ImageExtractor 插件的选项。

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | 返回 PdfExtractor 插件数据集合。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | 返回操作名称 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | 将新的数据源添加到 PdfExtractor 插件数据集合中。 |

## Remarks

`PdfExtractorOptions` 包含添加表示输入 PDF 文档的数据（文件、流）的基本功能。请创建 [`TextExtractorOptions`](../textextractoroptions/) 或 ImageExtractorOptions，而不是使用这个。

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)