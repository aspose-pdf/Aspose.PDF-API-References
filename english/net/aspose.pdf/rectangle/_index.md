---
title: "Rectangle Class"
linktitle: "Rectangle"
articleTitle: "Rectangle"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Rectangle class. Class represents rectangle."
type: docs
weight: 2600
url: "/net/aspose.pdf/rectangle/"
keywords: "Rectangle, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Rectangle class

Class represents rectangle.

```csharp
public sealed class Rectangle : ICloneable
```

## Constructors

| Name | Description |
| --- | --- |
| [Rectangle](./rectangle/)(double, double, double, double, bool) | Constructor of Rectangle. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](./empty/) { get; } | Empty rectangle |
| [Height](./height/) { get; } | Height of rectangle. |
| [IsEmpty](./isempty/) { get; } | Checks if rectangle is empty. |
| [IsPoint](./ispoint/) { get; } | Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY. |
| [IsTrivial](./istrivial/) { get; } | Checks if rectangle is trivial i.e. has zero size and position. |
| [LLX](./llx/) { get; set; } | X-coordinate of lower - left corner. |
| [LLY](./lly/) { get; set; } | Y - coordinate of lower-left corner. |
| static [Trivial](./trivial/) { get; } | Initializes trivial rectangle i.e. rectangle with zero position and size. |
| [URX](./urx/) { get; set; } | X - coordinate of upper-right corner. |
| [URY](./ury/) { get; set; } | Y - coordinate of upper-right corner. |
| [Width](./width/) { get; } | Width of rectangle. |

## Methods

| Name | Description |
| --- | --- |
| [Center](./center/)() | Returncs coordinates of center of the rectangle. |
| [Clone](./clone/)() | Clones the Rectangle object. |
| [Contains](./contains/)(Point, bool) | Determinces whether given point is inside of the rectangle. |
| [ContainsLine](./containsline/)(double, double, double, double) | Determines whether the rectangle contains a line represented by two points. |
| [ContainsPoint](./containspoint/)(double, double) | Determines whether the given point is contained within the rectangle. |
| [Equals](./equals/)(Rectangle) | Check if rectangles are equal i.e. have same position and sizes. |
| static [FromRect](./fromrect/)(Rectangle) | Initializes new rectangle from given instance of System.Drawing.Rectangle. |
| static [FromRect](./fromrect/)(RectangleF) | Initializes new rectangle from given instance of System.Drawing.Rectangle. |
| [Intersect](./intersect/)(Rectangle) | Intersects to rectangles. |
| [IsIntersect](./isintersect/)(Rectangle) | Determines whether this rectangle intersects with other rectangle. |
| [Join](./join/)(Rectangle) | Joins rectangles. |
| [MoveBy](./moveby/)(double, double) | Shift rectangle by the specified deltas. |
| [NearEquals](./nearequals/)(Rectangle, double) | Check if rectangles are near equal i.e. have near same (up to delta) position and sizes. |
| static [Parse](./parse/)(string) | Try to parse string and extract from it rectangle components llx, lly, urx, ury. |
| [Rotate](./rotate/)(int) | Rotate rectangle by the specified angle. |
| [Rotate](./rotate/)(Rotation) | Rotate rectangle by the specified angle. |
| [ToPoints](./topoints/)() | Converts rectangle into array of points ("QuadPoints"). |
| [ToRect](./torect/)() | Converts rectangle to instance of System.Drawing.Rectangle. Floating-point positions and size are truncated. |
| override [ToString](./tostring/)() | Gets rectangle string representation. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

