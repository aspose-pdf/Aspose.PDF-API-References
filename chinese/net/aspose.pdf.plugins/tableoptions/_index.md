---
title: "类 TableOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TableOptions 类。表示通过 TableGenerator 插件向文档添加表格的选项"
type: docs
weight: 9510
url: /zh/net/aspose.pdf.plugins/tableoptions/
---
## TableOptions class

表示通过 [`TableGenerator`](../tablegenerator/) 插件向文档添加表格的选项。

```csharp
public sealed class TableOptions : PdfGeneratorOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TableOptions](tableoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfgeneratoroptions/inputs/) { get; } | 返回 PdfGenerator 插件的数据集合。 |
| [Outputs](../../aspose.pdf.plugins/pdfgeneratoroptions/outputs/) { get; } | 获取已添加目标的集合，用于保存操作结果。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.plugins/tableoptions/create/)() | 创建 `TableOptions` 实例。 |
| [AddInput](../../aspose.pdf.plugins/pdfgeneratoroptions/addinput/)(IDataSource) | 向 PdfGenerator 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdfgeneratoroptions/addoutput/)(IDataSource) | 向 PdfGenerator 插件的数据集合添加新数据源。 |
| [AddTable](../../aspose.pdf.plugins/tableoptions/addtable/)() | 向文档添加表格。 |
| [InsertPageAfter](../../aspose.pdf.plugins/tableoptions/insertpageafter/)(int) | 在指定页面之后插入页面。 |
| [InsertPageBefore](../../aspose.pdf.plugins/tableoptions/insertpagebefore/)(int) | 在指定页面之前插入页面。 |

### 另请参见

* class [PdfGeneratorOptions](../pdfgeneratoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


