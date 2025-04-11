---
title: Class PdfToDocOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToDocOptions class. 表示 DocConverter 插件的 PDF 到 DOC 转换器选项
type: docs
weight: 9090
url: /zh/net/aspose.pdf.plugins/pdftodocoptions/
---
## PdfToDocOptions class

表示 [`DocConverter`](../docconverter/) 插件的 PDF 到 DOC 转换器选项。

```csharp
public sealed class PdfToDocOptions : PdfConverterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfToDocOptions](pdftodocoptions/#constructor)() | 使用默认选项初始化 `PdfToDocOptions` 对象的新实例。 |
| [PdfToDocOptions](pdftodocoptions/#constructor_1)(SaveFormat, ConversionMode) | 为指定的格式和模式初始化 `PdfToDocOptions` 对象的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftodocoptions/conversionmode/) { get; set; } | 允许控制 PDF 文档如何转换为文字处理文档。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | 返回 PdfConverterOptions 插件数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/pdftodocoptions/operationname/) { get; } | 获取操作的名称。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 获取添加的目标集合以保存操作结果。 |
| [SaveFormat](../../aspose.pdf.plugins/pdftodocoptions/saveformat/) { get; set; } | 输出文档的保存格式。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | 向 PdfConverter 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | 向 PdfToXLSXConverterOptions 插件数据集合添加新的数据源。 |

### See Also

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)