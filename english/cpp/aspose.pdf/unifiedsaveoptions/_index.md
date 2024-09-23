---
title: Aspose::Pdf::UnifiedSaveOptions class
linktitle: UnifiedSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::UnifiedSaveOptions class. This class represents saving options for saving that uses unified conversion way (with unified internal document model) in C++.'
type: docs
weight: 15700
url: /cpp/aspose.pdf/unifiedsaveoptions/
---
## UnifiedSaveOptions class


This class represents saving options for saving that uses unified conversion way (with unified internal document model)

```cpp
class UnifiedSaveOptions : public Aspose::Pdf::SaveOptions
```

## Nested classes

* Class [ProgressEventHandlerInfo](./progresseventhandlerinfo/)
## Methods

| Method | Description |
| --- | --- |
| [get_ExtractOcrSublayerOnly](./get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_ExtractOcrSublayerOnly](./set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [UnifiedSaveOptions](./unifiedsaveoptions/)() |  |
## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](./ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](./trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ConversionProgressEventHandler](./conversionprogresseventhandler/) |  |



## See Also

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
