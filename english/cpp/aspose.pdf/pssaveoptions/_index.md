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
| [get_EmbedFont](./get_embedfont/)() const | Gets/sets flag that indicates if fonts must be embedded in resulting PS document. |
| [get_EmbedFontAs](./get_embedfontas/)() const | Gets/sets type in which fonts must be embedded in resulting PS document. |
| [PsSaveOptions](./pssaveoptions/)() | Constructor. |
| [PsSaveOptions](./pssaveoptions/)(Aspose::Pdf::SaveFormat) | Constructor. |
| [set_EmbedFont](./set_embedfont/)(bool) | Gets/sets flag that indicates if fonts must be embedded in resulting PS document. |
| [set_EmbedFontAs](./set_embedfontas/)(System::String) | Gets/sets type in which fonts must be embedded in resulting PS document. |
## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
