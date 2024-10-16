---
title: Aspose::Pdf::SvgSaveOptions class
linktitle: SvgSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SvgSaveOptions class. Save options for export to SVG format in C++.'
type: docs
weight: 14500
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
## Fields

| Field | Description |
| --- | --- |
| [CompressOutputToZipArchive](./compressoutputtoziparchive/) | Specifies whether output will be created as one zip-archive. Please refer comment to 'TreatTargetFileNameAsDirectory' options to see rules of naming of svg-files of pages for multipage source document, that are also applied to zipped set of output files. |
| [CustomStrategyOfEmbeddedImagesSaving](./customstrategyofembeddedimagessaving/) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [ScaleToPixels](./scaletopixels/) | Specifies whether to scale the output document from typographic points to pixels. |
| [TreatTargetFileNameAsDirectory](./treattargetfilenameasdirectory/) | This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. It so, that directory will contain all output SVG-images of pages (like described below). If no, output files of pages other then first one will be created exactly in requested directory as main output file, but will contain in file name suffix _[2...n], that is defined by page number, f.e. if You define output file "C:\AsposeTests\output.svg" and output will contain several svg-files of pages, then files of pages will be created also in directory "C:\AsposeTests\" and have names 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [EmbeddedImagesSavingStrategy](./embeddedimagessavingstrategy/) |  |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
