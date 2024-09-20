---
title: Aspose::Pdf::LaTeXSaveOptions class
linktitle: LaTeXSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LaTeXSaveOptions class. Save options for export to TeX format in C++.'
type: docs
weight: 8100
url: /cpp/aspose.pdf/latexsaveoptions/
---
## LaTeXSaveOptions class


Save options for export to TeX format.

```cpp
class LaTeXSaveOptions : public Aspose::Pdf::TeXSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [AddFontEncs](../texsaveoptions/addfontencs/)(const System::ArrayPtr\<System::String\>\&) | Adds a font ancoding to the font encoding list. |
| [ClearFontEncs](../texsaveoptions/clearfontencs/)() | Clears the font encoding list. |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_ExtractOcrSublayerOnly](../unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_OutDirectoryPath](../texsaveoptions/get_outdirectorypath/)() const | Property for **_outDirectoryPath** parameter. |
| [get_PagesCount](../texsaveoptions/get_pagescount/)() const | Returns the number of pages after conversion. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_ExtractOcrSublayerOnly](../unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_OutDirectoryPath](../texsaveoptions/set_outdirectorypath/)(System::String) | Property for **_outDirectoryPath** parameter. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [TeXSaveOptions](../texsaveoptions/texsaveoptions/)() | Initializes a new instance of the [TeXSaveOptions](../texsaveoptions/) class. |
| [UnifiedSaveOptions](../unifiedsaveoptions/unifiedsaveoptions/)() |  |

## Deprecated
Use TeXSaveOptions instead 

## See Also

* Class [TeXSaveOptions](../texsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
