---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions class. 表示用于 XlsConverter 插件的 PDF 到 XLSX 转换器选项
type: docs
weight: 9150
url: /zh/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

表示用于 [`XlsConverter`](../xlsconverter/) 插件的 PDF 到 XLSX 转换器选项。

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | 输出格式。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | 返回 PdfConverterOptions 插件数据集合。 |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | 如果需要将空白列插入为工作表的第一列，则设置为 true。默认值为 false；这意味着不会插入空白列。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | 如果需要最小化结果工作簿中的工作表数量，则设置为 true。默认值为 false；这意味着将每个 PDF 页面保存为单独的工作表。 |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | 获取操作的名称。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 获取添加的目标集合以保存操作结果。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | 将新数据源添加到 PdfConverter 插件数据集合。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | 将新数据源添加到 PdfToXLSXConverterOptions 插件数据集合。 |

## Other Members

| Name | Description |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | 允许指定 .xlsx、.xls/xml 或 csv 文件格式。默认值为 XLSX。 |

### See Also

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)