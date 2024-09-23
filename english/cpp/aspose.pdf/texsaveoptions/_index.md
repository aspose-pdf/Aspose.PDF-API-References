---
title: Aspose::Pdf::TeXSaveOptions class
linktitle: TeXSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXSaveOptions class. Save options for export to TeX format in C++.'
type: docs
weight: 15200
url: /cpp/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class


Save options for export to TeX format.

```cpp
class TeXSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [AddFontEncs](./addfontencs/)(const System::ArrayPtr\<System::String\>\&) | Adds a font ancoding to the font encoding list. |
| [ClearFontEncs](./clearfontencs/)() | Clears the font encoding list. |
| [get_OutDirectoryPath](./get_outdirectorypath/)() const | Property for **_outDirectoryPath** parameter. |
| [get_PagesCount](./get_pagescount/)() const | Returns the number of pages after conversion. |
| [set_OutDirectoryPath](./set_outdirectorypath/)(System::String) | Property for **_outDirectoryPath** parameter. |
| [TeXSaveOptions](./texsaveoptions/)() | Initializes a new instance of the [TeXSaveOptions](./) class. |
## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
