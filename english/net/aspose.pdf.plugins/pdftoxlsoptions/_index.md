---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions class. Represents PDF to XLSX converter options for XlsConverter plugin
type: docs
weight: 9300
url: /net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

Represents PDF to XLSX converter options for [`XlsConverter`](../xlsconverter/) plugin.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Output format. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Returns PdfConverterOptions plugin data collection. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Gets name of the operation. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Gets collection of added targets for saving operation results. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Adds new data source to the PdfConverter plugin data collection. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Adds new data source to the PdfToXLSXConverterOptions plugin data collection. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Allows to specify .xlsx, .xls/xml or csv file format. Default value is XLSX. |

### See Also

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


