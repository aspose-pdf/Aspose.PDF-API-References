---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: UnifiedSaveOptions field. Sometimes PDFs contain background images of pages or table cells constructed from several same tiling background images put one near other. In such case renderers of target formats f.e MsWord for DOCS format sometimes generates visible boundaries beetween parts of background images cause their techniques of image edge smoothing antialiasing is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images please try use this setting to get rid of that unwanted effect. ATTENTION This optimization of quality usually essentially slows down conversion so please use this option only when its really necessary
type: docs
weight: 30
url: /net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### See Also

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


