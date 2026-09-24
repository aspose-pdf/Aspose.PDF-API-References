---
title: "UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages"
linktitle: "TryMergeAdjacentSameBackgroundImages"
articleTitle: "TryMergeAdjacentSameBackgroundImages"
second_title: "Aspose.PDF for .NET"
description: "Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case re..."
type: docs
weight: 30
url: "/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/"
product_version: "26.9.0"
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

Sometimes PDFs contain background images (of pages or table cells)
 constructed from several same tiling background images put one near other.
 In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates
 visible boundaries beetween parts of background images,
 cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader.
 If it looks like exported document contains such visible boundaries between 
 parts of same background images, please try use this setting to get rid 
 of that unwanted effect. 
 ATTENTION! This optimization of quality usually essentially slows down conversion,
 so, please, use this option only when it's really necessary.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### See Also

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

