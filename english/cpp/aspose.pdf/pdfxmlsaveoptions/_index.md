---
title: Aspose::Pdf::PdfXmlSaveOptions class
linktitle: PdfXmlSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfXmlSaveOptions class. Save options for PdfXml format in C++.'
type: docs
weight: 12800
url: /cpp/aspose.pdf/pdfxmlsaveoptions/
---
## PdfXmlSaveOptions class


Save options for PdfXml format.

```cpp
class PdfXmlSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/)() | Constructor ofr PdfXml format. |
## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
