---
title: Aspose::Pdf::SvgSaveOptions class
linktitle: SvgSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SvgSaveOptions class. Save options for export to SVG format in C++.'
type: docs
weight: 17600
url: /cpp/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class


Save options for export to SVG format.

```cpp
class SvgSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Nested classes

* Class [SvgImageSavingInfo](./svgimagesavinginfo/)
## Enums

| Enum | Description |
| --- | --- |
| [SvgExternalImageType](./svgexternalimagetype/) | enumerates possible types of image files that can be saved as external resources during during [Pdf](../) to SVG conversion |
## Methods

| Method | Description |
| --- | --- |
| [SvgSaveOptions](./svgsaveoptions/)() | Constructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [EmbeddedImagesSavingStrategy](./embeddedimagessavingstrategy/) | To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like self-made saving into stream or on disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated SVG instead of original supposed path to that image resource. In such case all the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
