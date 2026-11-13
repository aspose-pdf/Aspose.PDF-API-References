---
title: PageExtensions.DuplicateIntersectingGraphics
second_title: Aspose.PDF for .NET API Reference
description: PageExtensions method. Finds all vector graphic elements that intersect with the specified region and creates their copies with offset from original positions
type: docs
weight: 10
url: /net/aspose.pdf/pageextensions/duplicateintersectinggraphics/
---
## PageExtensions.DuplicateIntersectingGraphics method

Finds all vector graphic elements that intersect with the specified region and creates their copies with offset from original positions.

```csharp
public static void DuplicateIntersectingGraphics(this Page page, Rectangle region, double deltaX, 
    double deltaY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page where graphic elements are searched and copied to. |
| region | Rectangle | The rectangular region to search for intersecting elements. |
| deltaX | Double | Offset along the X axis for copied elements. |
| deltaY | Double | Offset along the Y axis for copied elements. |

## Remarks

This method works only with vector graphics (lines, shapes, Bezier curves, etc.). Raster images and other types of elements are not processed. Each copied element will be shifted by the specified dx and dy values relative to its original position. The original elements remain unchanged.

### See Also

* class [Page](../../page/)
* class [Rectangle](../../rectangle/)
* class [PageExtensions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


