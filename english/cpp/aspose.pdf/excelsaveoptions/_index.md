---
title: Aspose::Pdf::ExcelSaveOptions class
linktitle: ExcelSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ExcelSaveOptions class. Save options for export to Excel format in C++.'
type: docs
weight: 4700
url: /cpp/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class


Save options for export to Excel format.

```cpp
class ExcelSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [ExcelFormat](./excelformat/) | Allows to specify .xlsx, .xls/xml or csv file format. Default value is XLSX;. |
## Methods

| Method | Description |
| --- | --- |
| [ExcelSaveOptions](./excelsaveoptions/)() | Constructor. |
| [get_Format](./get_format/)() const | Output format. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [get_UniformWorksheets](./get_uniformworksheets/)() const | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
| [set_Format](./set_format/)(ExcelSaveOptions::ExcelFormat) | Output format. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [set_UniformWorksheets](./set_uniformworksheets/)(bool) | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
