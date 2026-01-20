---
title: Aspose::Pdf::LowCode::PdfToXlsOptions class
linktitle: PdfToXlsOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfToXlsOptions class. Represents PDF to XLSX converter options for XlsConverter plugin in C++.'
type: docs
weight: 6600
url: /cpp/aspose.pdf.lowcode/pdftoxlsoptions/
---
## PdfToXlsOptions class


Represents PDF to XLSX converter options for [XlsConverter](../xlsconverter/) plugin.

```cpp
class PdfToXlsOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [ExcelFormat](./excelformat/) | Allows to specify .xlsx, .xls/xml or csv file format. Default value is XLSX. |
## Methods

| Method | Description |
| --- | --- |
| [get_Format](./get_format/)() const | Output format. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [get_OperationName](./get_operationname/)() override | Gets name of the operation. |
| [PdfToXlsOptions](./pdftoxlsoptions/)() | Initializes new instance of the [PdfToXlsOptions](./) object with default options. |
| [set_Format](./set_format/)(PdfToXlsOptions::ExcelFormat) | Output format. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
## See Also

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
