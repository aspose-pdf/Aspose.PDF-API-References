---
title: Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics method
linktitle: DuplicateIntersectingGraphics
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics method. Finds all vector graphic elements that intersect with the specified region and creates their copies with offset from original positions in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/pageextensions/duplicateintersectinggraphics/
---
## PageExtensions::DuplicateIntersectingGraphics method


Finds all vector graphic elements that intersect with the specified region and creates their copies with offset from original positions.

```cpp
static void Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics(System::SharedPtr<Page> page, System::SharedPtr<Rectangle> region, double deltaX, double deltaY)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page where graphic elements are searched and copied to. |
| region | System::SharedPtr\<Rectangle\> | The rectangular region to search for intersecting elements. |
| deltaX | double | Offset along the X axis for copied elements. |
| deltaY | double | Offset along the Y axis for copied elements. |
## Remarks



This method works only with vector graphics (lines, shapes, Bezier curves, etc.). Raster images and other types of elements are not processed. Each copied element will be shifted by the specified dx and dy values relative to its original position. The original elements remain unchanged. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [Rectangle](../../rectangle/)
* Class [PageExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
