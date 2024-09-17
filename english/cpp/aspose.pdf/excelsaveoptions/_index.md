---
title: Aspose::Pdf::ExcelSaveOptions class
linktitle: ExcelSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ExcelSaveOptions class. Save options for export to Excel format in C++.'
type: docs
weight: 4200
url: /cpp/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class


Save options for export to Excel format.

```cpp
class ExcelSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [ExcelSaveOptions](./excelsaveoptions/)() | Constructor. |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_ExtractOcrSublayerOnly](../unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_Format](./get_format/)() const | Output format. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_UniformWorksheets](./get_uniformworksheets/)() const | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_ExtractOcrSublayerOnly](../unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_Format](./set_format/)(ExcelSaveOptions::ExcelFormat) | Output format. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [set_UniformWorksheets](./set_uniformworksheets/)(bool) | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [UnifiedSaveOptions](../unifiedsaveoptions/unifiedsaveoptions/)() |  |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
