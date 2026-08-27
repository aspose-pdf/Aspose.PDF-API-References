---
title: "类 PdfExtractorOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfExtractorOptions 类。表示 TextExtractor 和 ImageExtractor 插件的选项"
type: docs
weight: 9220
url: /zh/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions class

表示 TextExtractor 和 ImageExtractor 插件的选项。

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | 返回 PdfExtractor 插件的数据集合。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | 返回操作名称 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | 向 PdfExtractor 插件的数据集合添加新的数据源。 |

## 备注

`PdfExtractorOptions` 包含用于添加表示输入 PDF 文档的数据（文件、流）的基础功能。请创建 [`TextExtractorOptions`](../textextractoroptions/) 或 ImageExtractorOptions 来代替此项。

### 另请参见

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


