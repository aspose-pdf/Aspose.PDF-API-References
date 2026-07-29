---
title: "类 PdfToXlsOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfToXlsOptions 类。表示用于 XlsConverter 插件的 PDF 转 XLSX 转换器选项"
type: docs
weight: 9300
url: /zh/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

表示用于 [`XlsConverter`](../xlsconverter/) 插件的 PDF 转 XLSX 转换器选项。

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | 输出格式。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | 返回 PdfConverterOptions 插件数据集合。 |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | 如果需要在工作表的第一列插入空列，请设为 true。默认值为 false；这意味着不会插入空列。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | 如果需要在生成的工作簿中最小化工作表数量，请设为 true。默认值为 false；这意味着每个 PDF 页面将保存为单独的工作表。 |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | 获取操作的名称。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 获取已添加目标的集合，用于保存操作结果。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | 向 PdfConverter 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | 向 PdfToXLSXConverterOptions 插件数据集合添加新的数据源。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | 允许指定 .xlsx、.xls/xml 或 csv 文件格式。默认值为 XLSX。 |

### 另请参见

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


