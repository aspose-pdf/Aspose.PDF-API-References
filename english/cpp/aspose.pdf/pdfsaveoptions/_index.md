---
title: Aspose::Pdf::PdfSaveOptions class
linktitle: PdfSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfSaveOptions class. Save options for export to Pdf format in C++.'
type: docs
weight: 12500
url: /cpp/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class


Save options for export to [Pdf](../) format.

```cpp
class PdfSaveOptions : public Aspose::Pdf::SaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [DefaultFontName](../) is found on device) |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_TempPath](./get_temppath/)() const | Path for temporary files. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [PdfSaveOptions](./pdfsaveoptions/)() | Constructor. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_DefaultFontName](./set_defaultfontname/)(System::String) | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [DefaultFontName](../) is found on device) |
| [set_TempPath](./set_temppath/)(System::String) | Path for temporary files. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
## See Also

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
