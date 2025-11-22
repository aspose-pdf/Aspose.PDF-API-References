---
title: Aspose::Pdf::Rectangle class
linktitle: Rectangle
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Rectangle class. Class represents rectangle in C++.'
type: docs
weight: 16300
url: /cpp/aspose.pdf/rectangle/
---
## Rectangle class


Class represents rectangle.

```cpp
class Rectangle : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Center](./center/)() | Returncs coordinates of center of the rectangle. |
| [Clone](./clone/)() override | Clones the [Rectangle](./) object. |
| [Contains](./contains/)(System::SharedPtr\<Point\>, bool) | Determinces whether given point is inside of the rectangle. |
| [ContainsLine](./containsline/)(double, double, double, double) | Determines whether the rectangle contains a line represented by two points. |
| [ContainsPoint](./containspoint/)(double, double) | Determines whether the given point is contained within the rectangle. |
| [Equals](./equals/)(System::SharedPtr\<Rectangle\>) | Check if rectangles are equal i.e. have same position and sizes. |
| static [FromRect](./fromrect/)(System::Drawing::Rectangle) | Initializes new rectangle from given instance of [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [FromRect](./fromrect/)(System::Drawing::RectangleF) | Initializes new rectangle from given instance of [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [get_Empty](./get_empty/)() | Empty rectangle. |
| [get_Height](./get_height/)() | Height of rectangle. |
| [get_IsEmpty](./get_isempty/)() const | Checks if rectangle is empty. |
| [get_IsPoint](./get_ispoint/)() | Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY. |
| [get_IsTrivial](./get_istrivial/)() | Checks if rectangle is trivial i.e. has zero size and position. |
| [get_LLX](./get_llx/)() const | X-coordinate of lower - left corner. |
| [get_LLY](./get_lly/)() const | Y - coordinate of lower-left corner. |
| static [get_Trivial](./get_trivial/)() | Initializes trivial rectangle i.e. rectangle with zero position and size. |
| [get_URX](./get_urx/)() const | X - coordinate of upper-right corner. |
| [get_URY](./get_ury/)() const | Y - coordinate of upper-right corner. |
| [get_Width](./get_width/)() | Width of rectangle. |
| [Intersect](./intersect/)(System::SharedPtr\<Rectangle\>) | Intersects to rectangles. |
| [IsIntersect](./isintersect/)(System::SharedPtr\<Rectangle\>) | Determines whether this rectangle intersects with other rectangle. |
| [Join](./join/)(System::SharedPtr\<Rectangle\>) | Joins rectangles. |
| [MoveBy](./moveby/)(double, double) | Shift rectangle by the specified deltas. |
| [NearEquals](./nearequals/)(System::SharedPtr\<Rectangle\>, double) | Check if rectangles are near equal i.e. have near same (up to delta) position and sizes. |
| static [Parse](./parse/)(System::String) | Try to parse string and extract from it rectangle components llx, lly, urx, ury. |
| [Rectangle](./rectangle/)(double, double, double, double, bool) | Constructor of [Rectangle](./). |
| [Rotate](./rotate/)(Rotation) | Rotate rectangle by the specified angle. |
| [Rotate](./rotate/)(int32_t) | Rotate rectangle by the specified angle. |
| [set_LLX](./set_llx/)(double) | X-coordinate of lower - left corner. |
| [set_LLY](./set_lly/)(double) | Y - coordinate of lower-left corner. |
| [set_URX](./set_urx/)(double) | X - coordinate of upper-right corner. |
| [set_URY](./set_ury/)(double) | Y - coordinate of upper-right corner. |
| [ToPoints](./topoints/)() | Converts rectangle into array of points ("QuadPoints"). |
| [ToRect](./torect/)() | Converts rectangle to instance of [System.Drawing.Rectangle](../../system.drawing/rectangle/). Floating-point positions and size are truncated. |
| [ToString](./tostring/)() const override | Gets rectangle string representation. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
