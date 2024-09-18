---
title: Aspose::Pdf::PptxSaveOptions class
linktitle: PptxSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PptxSaveOptions class. Save options for export to SVG format in C++.'
type: docs
weight: 13100
url: /cpp/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class


Save options for export to SVG format.

```cpp
class PptxSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_CustomProgressHandler](./get_customprogresshandler/)() const | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [get_ExtractOcrSublayerOnly](../unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_ImageResolution](./get_imageresolution/)() const | Gets the image resolution (dpi). Default is 192 dpi. |
| [get_OptimizeTextBoxes](./get_optimizetextboxes/)() const | Toggles text columns recognition. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_SeparateImages](./get_separateimages/)() const | If set to true then images are separated from all other graphics. |
| [get_SlidesAsImages](./get_slidesasimages/)() const | If set to true then all the content is recognized as images (one per page) |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [PptxSaveOptions](./pptxsaveoptions/)() | Constructor. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_CustomProgressHandler](./set_customprogresshandler/)(UnifiedSaveOptions::ConversionProgressEventHandler) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [set_ExtractOcrSublayerOnly](../unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Sets the image resolution (dpi). Default is 192 dpi. |
| [set_OptimizeTextBoxes](./set_optimizetextboxes/)(bool) | Toggles text columns recognition. |
| [set_SeparateImages](./set_separateimages/)(bool) | If set to true then images are separated from all other graphics. |
| [set_SlidesAsImages](./set_slidesasimages/)(bool) | If set to true then all the content is recognized as images (one per page) |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [UnifiedSaveOptions](../unifiedsaveoptions/unifiedsaveoptions/)() |  |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
