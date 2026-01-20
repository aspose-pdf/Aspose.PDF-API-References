---
title: Aspose::Pdf::PptxSaveOptions class
linktitle: PptxSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PptxSaveOptions class. Save options for export to SVG format in C++.'
type: docs
weight: 15800
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
| [get_CustomProgressHandler](./get_customprogresshandler/)() const | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [get_ImageResolution](./get_imageresolution/)() const | Gets the image resolution (dpi). Default is 192 dpi. |
| [get_OptimizeTextBoxes](./get_optimizetextboxes/)() const | Toggles text columns recognition. |
| [get_SeparateImages](./get_separateimages/)() const | If set to true then images are separated from all other graphics. |
| [get_SlidesAsImages](./get_slidesasimages/)() const | If set to true then all the content is recognized as images (one per page) |
| [PptxSaveOptions](./pptxsaveoptions/)() | Constructor. |
| [set_CustomProgressHandler](./set_customprogresshandler/)(UnifiedSaveOptions::ConversionProgressEventHandler) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Sets the image resolution (dpi). Default is 192 dpi. |
| [set_OptimizeTextBoxes](./set_optimizetextboxes/)(bool) | Toggles text columns recognition. |
| [set_SeparateImages](./set_separateimages/)(bool) | If set to true then images are separated from all other graphics. |
| [set_SlidesAsImages](./set_slidesasimages/)(bool) | If set to true then all the content is recognized as images (one per page) |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
