---
title: System::Drawing::RectangleF class
linktitle: RectangleF
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::RectangleF class. Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 2000
url: /cpp/system.drawing/rectanglef/
---
## RectangleF class


Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class RectangleF
```

## Methods

| Method | Description |
| --- | --- |
| [Contains](./contains/)(float, float) | Determines if the specified point is located within the rectangle represented by the current object. |
| [Contains](./contains/)(const PointF\&) | Determines if the specified point is located within the rectangle represented by the current object. |
| [Contains](./contains/)(const RectangleF\&) | Determines if the specified rectangle is located within the rectangle represented by the current object. |
| [Equals](./equals/)(const RectangleF\&) const | Determines if the rectangles represented by the current and the specified objects are identical. |
| static [FromLTRB](./fromltrb/)(float, float, float, float) | Constructs a new [RectangleF](./) object that represents a rectangle with the specified edge locations. |
| [get_Bottom](./get_bottom/)() const | Returns the y coordinate of the bottom edge of the rectangle represented by the current object. |
| [get_Height](./get_height/)() const | Returns the height of the rectangle represented by the current object. |
| [get_IsEmpty](./get_isempty/)() const | Determines if X and Y coordinates of the upper left corner of the recangle represented by the current object as well as its width and height have values of 0. |
| [get_Left](./get_left/)() const | Returns the X coordinate of the left edge of the rectangle represented by the current object. |
| [get_Location](./get_location/)() const | Returns an instance of the [PointF](../pointf/) class that specifies the location of the upper left corner of the rectangle represented by the current object. |
| [get_Right](./get_right/)() const | Returns the X coordinate of the right edge of the rectangle represented by the current object. |
| [get_Size](./get_size/)() const | Returns an instance of the [SizeF](../sizef/) class that specifies the width and height of the rectangle represented by the current object. |
| [get_Top](./get_top/)() const | Returns the Y coordinate of the top edge of the rectangle represented by the current object. |
| [get_Width](./get_width/)() const | Returns the width of the rectangle represented by the current object. |
| [get_X](./get_x/)() const | Returns the X coordinate of the upper left corner of the rectangle represented by the current object. |
| [get_Y](./get_y/)() const | Returns the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code of the current object. |
| [Inflate](./inflate/)(float, float) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| [Inflate](./inflate/)(const SizeF\&) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly. |
| static [Inflate](./inflate/)(const RectangleF\&, float, float) | Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| [Intersect](./intersect/)(const RectangleF\&) | Replaces the rectangle represented by the current object with the rectangle that results from the its intersection with the rectangle represented by the specified object. |
| static [Intersect](./intersect/)(const RectangleF\&, const RectangleF\&) | Returns a rectangle that is a result of intersection of the specified rectangles. |
| [IntersectsWith](./intersectswith/)(const RectangleF\&) | Determines if the rectangles represented by the current and specified objects intesect. |
| [Offset](./offset/)(const PointF\&) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| [Offset](./offset/)(float, float) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Always returns true. |
| [operator==](./operator==/)(std::nullptr_t) const | Always returns false. |
| [RectangleF](./rectanglef/)() | Constructs a new instance of [RectangleF](./) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0. |
| [RectangleF](./rectanglef/)(float, float, float, float) | Constructs a new instance of [RectangleF](./) object that represents a rectangle with the specified coordinates of its upper left corner and width and height. |
| [RectangleF](./rectanglef/)(const PointF\&, const SizeF\&) | Constructs a new instance of [RectangleF](./) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [PointF](../pointf/) class and its width and height as an instance of [SizeF](../sizef/) class. |
| explicit [RectangleF](./rectanglef/)(const Rectangle\&) | Constructs a new instance of [RectangleF](./) object that represents the rectangle equivalent to the specified one. |
| [set_Height](./set_height/)(float) | Sets the height of the rectangle represented by the current object. |
| [set_Location](./set_location/)(PointF) | Sets the location of the upper left corner of the rectangle represented by the current object. |
| [set_Size](./set_size/)(SizeF) | Sets the width and height of the rectangle represented by the current object. |
| [set_Width](./set_width/)(float) | Sets the width of the rectangle represented by the current object. |
| [set_X](./set_x/)(float) | Sets the X coordinate of the upper left corner of the rectangle represented by the current object. |
| [set_Y](./set_y/)(float) | Sets the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| [ToString](./tostring/)() const | Returns the string representation of the current object. |
| static [Union](./union/)(const RectangleF\&, const RectangleF\&) | Returns a rectangle that is a result of union of the specified rectangles. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty rectangle i.e. a rectangle whose location and size values have zero values. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
