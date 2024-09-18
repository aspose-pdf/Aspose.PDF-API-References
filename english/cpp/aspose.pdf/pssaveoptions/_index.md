---
title: Aspose::Pdf::PsSaveOptions class
linktitle: PsSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PsSaveOptions class. Save options for export to PS (PostScript) or EPS format in C++.'
type: docs
weight: 13500
url: /cpp/aspose.pdf/pssaveoptions/
---
## PsSaveOptions class


Save options for export to PS (PostScript) or EPS format.

```cpp
class PsSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_EmbedFont](./get_embedfont/)() const | Gets/sets flag that indicates if fonts must be embedded in resulting PS document. |
| [get_EmbedFontAs](./get_embedfontas/)() const | Gets/sets type in which fonts must be embedded in resulting PS document. |
| [get_ExtractOcrSublayerOnly](../unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [PsSaveOptions](./pssaveoptions/)() | Constructor. |
| [PsSaveOptions](./pssaveoptions/)(Aspose::Pdf::SaveFormat) | Constructor. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_EmbedFont](./set_embedfont/)(bool) | Gets/sets flag that indicates if fonts must be embedded in resulting PS document. |
| [set_EmbedFontAs](./set_embedfontas/)(System::String) | Gets/sets type in which fonts must be embedded in resulting PS document. |
| [set_ExtractOcrSublayerOnly](../unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [UnifiedSaveOptions](../unifiedsaveoptions/unifiedsaveoptions/)() |  |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
