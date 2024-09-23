---
title: Aspose::Pdf::UnifiedSaveOptions::TryMergeAdjacentSameBackgroundImages field
linktitle: TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::UnifiedSaveOptions::TryMergeAdjacentSameBackgroundImages field. Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it''s really necessary in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## TryMergeAdjacentSameBackgroundImages field


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

```cpp
bool Aspose::Pdf::UnifiedSaveOptions::TryMergeAdjacentSameBackgroundImages
```

## See Also

* Class [UnifiedSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
