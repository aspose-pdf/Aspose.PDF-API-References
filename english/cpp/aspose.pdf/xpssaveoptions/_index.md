---
title: Aspose::Pdf::XpsSaveOptions class
linktitle: XpsSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XpsSaveOptions class. Save options for export to Xps format in C++.'
type: docs
weight: 20100
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
| [get_SaveTransparentTexts](./get_savetransparenttexts/)() const | Indicates whether to preserve transparent (OCR'ed) text. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Gets UseNewImagingEngine option. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [set_SaveTransparentTexts](./set_savetransparenttexts/)(bool) | Indicates whether to preserve transparent (OCR'ed) text. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Sets UseNewImagingEngine option. |
| [XpsSaveOptions](./xpssaveoptions/)() | Constructor. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
