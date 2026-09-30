---
title: "PdfToXlsOptions Class"
linktitle: "PdfToXlsOptions"
articleTitle: "PdfToXlsOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.PdfToXlsOptions class. Represents PDF to XLSX converter options for XlsConverter plugin."
type: docs
weight: 740
url: "/net/aspose.pdf.lowcode/pdftoxlsoptions/"
keywords: "PdfToXlsOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfToXlsOptions class

Represents PDF to XLSX converter options for [`XlsConverter`](../../aspose.pdf.lowcode/xlsconverter/) plugin.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfToXlsOptions](./pdftoxlsoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Format](./format/) { get; set; } | Output format. |
| [Inputs](../../aspose.pdf.lowcode/pdfconverteroptions/inputs/) { get; } | Returns PdfConverterOptions plugin data collection. |
| [InsertBlankColumnAtFirst](./insertblankcolumnatfirst/) { get; set; } | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [MinimizeTheNumberOfWorksheets](./minimizethenumberofworksheets/) { get; set; } | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| override [OperationName](./operationname/) { get; } | Gets name of the operation. |
| [Outputs](../../aspose.pdf.lowcode/pdfconverteroptions/outputs/) { get; } | Gets collection of added targets for saving operation results. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdfconverteroptions/addinput/)(IDataSource) | Adds new data source to the PdfConverter plugin data collection. |
| [AddOutput](../../aspose.pdf.lowcode/pdfconverteroptions/addoutput/)(IDataSource) | Adds new data source to the PdfToXLSXConverterOptions plugin data collection. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.lowcode/pdftoxlsoptions.excelformat) | Allows to specify .xlsx, .xls/xml or csv file format. Default value is XLSX. |

### See Also

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

