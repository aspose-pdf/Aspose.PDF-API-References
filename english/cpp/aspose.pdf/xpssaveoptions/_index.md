---
title: Aspose::Pdf::XpsSaveOptions class
linktitle: XpsSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XpsSaveOptions class. Save options for export to Xps format in C++.'
type: docs
weight: 17800
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
## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
