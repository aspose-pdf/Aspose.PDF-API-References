---
title: Aspose::Pdf::EpubSaveOptions class
linktitle: EpubSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::EpubSaveOptions class. Save options for export to EPUB format in C++.'
type: docs
weight: 4100
url: /cpp/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions class


Save options for export to EPUB format.

```cpp
class EpubSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [RecognitionMode](./recognitionmode/) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content. |
## Methods

| Method | Description |
| --- | --- |
| [EpubSaveOptions](./epubsaveoptions/)() | Constructor. |
| [get_Title](./get_title/)() const | Gets EPUB document title. |
| [set_Title](./set_title/)(System::String) | Sets EPUB document title. |
## Fields

| Field | Description |
| --- | --- |
| [ContentRecognitionMode](./contentrecognitionmode/) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content. |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
