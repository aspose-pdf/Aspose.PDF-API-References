---
title: Aspose::Pdf::SvgSaveOptions::CustomStrategyOfEmbeddedImagesSaving field
linktitle: CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SvgSaveOptions::CustomStrategyOfEmbeddedImagesSaving field. This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter''s code itself, not in custom code, please set in custom code flag ''CustomProcessingCancelled'' of ''imageSavingInfo'' parameter''s variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code  in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## CustomStrategyOfEmbeddedImagesSaving field


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

```cpp
SvgSaveOptions::EmbeddedImagesSavingStrategy Aspose::Pdf::SvgSaveOptions::CustomStrategyOfEmbeddedImagesSaving
```

## See Also

* Class [SvgSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
