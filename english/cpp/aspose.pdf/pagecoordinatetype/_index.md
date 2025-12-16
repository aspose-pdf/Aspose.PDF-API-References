---
title: Aspose::Pdf::PageCoordinateType enum
linktitle: PageCoordinateType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCoordinateType enum. Describes page coordinate type in C++.'
type: docs
weight: 25200
url: /cpp/aspose.pdf/pagecoordinatetype/
---
## PageCoordinateType enum


Describes page coordinate type.

```cpp
enum class PageCoordinateType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MediaBox | 0 | The MediaBox is used to specify the width and height of the page. For the average user, this probably equals the actual page size. The MediaBox is the largest page box in a PDF. The other page boxes can equal the size of the MediaBox but they cannot be larger. |
| CropBox | 1 | The CropBox defines the region to which the page contents are to be clipped. Acrobat uses this size for screen display and printing. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
