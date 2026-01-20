---
title: Aspose::Pdf::XpsSaveOptions class
linktitle: XpsSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XpsSaveOptions class. Save options for export to Xps format in C++.'
type: docs
weight: 21100
url: /cpp/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class


Save options for export to Xps format.

```cpp
class XpsSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_BatchSize](./get_batchsize/)() override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [get_DefaultFont](./get_defaultfont/)() const | Gets/sets the default font name. Used if the embedded font name is not found in the system. |
| [get_SaveTransparentTexts](./get_savetransparenttexts/)() const | Indicates whether to preserve transparent (OCR'ed) text. |
| [get_UseEmbeddedTrueTypeFonts](./get_useembeddedtruetypefonts/)() const | Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Gets UseNewImagingEngine option. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [set_DefaultFont](./set_defaultfont/)(System::String) | Gets/sets the default font name. Used if the embedded font name is not found in the system. |
| [set_SaveTransparentTexts](./set_savetransparenttexts/)(bool) | Indicates whether to preserve transparent (OCR'ed) text. |
| [set_UseEmbeddedTrueTypeFonts](./set_useembeddedtruetypefonts/)(bool) | Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Sets UseNewImagingEngine option. |
| [XpsSaveOptions](./xpssaveoptions/)() | Constructor. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
