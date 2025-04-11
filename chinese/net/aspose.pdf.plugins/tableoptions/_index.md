---
title: Class TableOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableOptions class. 表示通过 TableGenerator 插件将表添加到文档的选项
type: docs
weight: 9360
url: /zh/net/aspose.pdf.plugins/tableoptions/
---
## TableOptions class

表示通过 [`TableGenerator`](../tablegenerator/) 插件将表添加到文档的选项。

```csharp
public sealed class TableOptions : PdfGeneratorOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TableOptions](tableoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfgeneratoroptions/inputs/) { get; } | 返回 PdfGenerator 插件数据集合。 |
| [Outputs](../../aspose.pdf.plugins/pdfgeneratoroptions/outputs/) { get; } | 获取用于保存操作结果的添加目标集合。 |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.pdf.plugins/tableoptions/create/)() | 创建 `TableOptions` 实例。 |
| [AddInput](../../aspose.pdf.plugins/pdfgeneratoroptions/addinput/)(IDataSource) | 将新数据源添加到 PdfGenerator 插件数据集合。 |
| [AddOutput](../../aspose.pdf.plugins/pdfgeneratoroptions/addoutput/)(IDataSource) | 将新数据源添加到 PdfGenerator 插件数据集合。 |
| [AddTable](../../aspose.pdf.plugins/tableoptions/addtable/)() | 将表添加到文档。 |
| [InsertPageAfter](../../aspose.pdf.plugins/tableoptions/insertpageafter/)(int) | 在指定页面后插入页面。 |
| [InsertPageBefore](../../aspose.pdf.plugins/tableoptions/insertpagebefore/)(int) | 在指定页面前插入页面。 |

### See Also

* class [PdfGeneratorOptions](../pdfgeneratoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)