---
title: System::Drawing::Rectangle class
linktitle: Rectangle
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Rectangle class. Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1900
url: /cpp/system.drawing/rectangle/
---
## Rectangle class


Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Rectangle
```

## Methods

| Method | Description |
| --- | --- |
| static [Ceiling](./ceiling/)(const RectangleF\&) | Constructs a [Rectangle](./) object from the specified [RectangleF](../rectanglef/) object by rounding the [RectangleF](../rectanglef/) object's location and size values to the next higher integer values. |
| [Contains](./contains/)(int, int) const | Determines if the specified point is located within the rectangle represented by the current object. |
| [Contains](./contains/)(const Point\&) const | Determines if the specified point is located within the rectangle represented by the current object. |
| [Contains](./contains/)(const Rectangle\&) const | Determines if the specified rectangle is located within the rectangle represented by the current object. |
| [Equals](./equals/)(const Rectangle\&) const | Determines if the rectangles represented by the current and the specified objects are identical. |
| static [FromLTRB](./fromltrb/)(int, int, int, int) | Constructs a new [Rectangle](./) object that represents a rectangle with the specified edge locations. |
| [get_Bottom](./get_bottom/)() const | Returns the y coordinate of the bottom edge of the rectangle represented by the current object. |
| [get_Height](./get_height/)() const | Returns the height of the rectangle represented by the current object. |
| [get_IsEmpty](./get_isempty/)() const | Determines if X and Y coordinates of the upper left corner of the recangle represented by the current object as well as its width and height have values of 0. |
| [get_Left](./get_left/)() const | Returns the X coordinate of the left edge of the rectangle represented by the current object. |
| [get_Location](./get_location/)() const | Returns an instance of the [Point](../point/) class that specifies the location of the upper left corner of the rectangle represented by the current object. |
| [get_Right](./get_right/)() const | Returns the X coordinate of the right edge of the rectangle represented by the current object. |
| [get_Size](./get_size/)() const | Returns an instance of the [Size](../size/) class that specifies the width and height of the rectangle represented by the current object. |
| [get_Top](./get_top/)() const | Returns the Y coordinate of the top edge of the rectangle represented by the current object. |
| [get_Width](./get_width/)() const | Returns the width of the rectangle represented by the current object. |
| [get_X](./get_x/)() const | Returns the X coordinate of the upper left corner of the rectangle represented by the current object. |
| [get_Y](./get_y/)() const | Returns the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code of the current object. |
| [Inflate](./inflate/)(int, int) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| [Inflate](./inflate/)(const Size\&) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly. |
| static [Inflate](./inflate/)(const Rectangle\&, int, int) | Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| [Intersect](./intersect/)(const Rectangle\&) | Replaces the rectangle represented by the current object with the rectangle that results from the its intersection with the rectangle represented by the specified object. |
| static [Intersect](./intersect/)(const Rectangle\&, const Rectangle\&) | Returns a rectangle that is a result of intersection of the specified rectangles. |
| [IntersectsWith](./intersectswith/)(const Rectangle\&) | Determines if the rectangles represented by the current and specified objects intesect. |
| [Offset](./offset/)(const Point\&) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| [Offset](./offset/)(int, int) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| [operator RectangleF](./operatorrectanglef/)() const | Returns a [RectangleF](../rectanglef/) object that represents a rectangle equivalent to the rectangle represented by the current object. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Always returns true. |
| [operator==](./operator==/)(std::nullptr_t) const | Always returns false. |
| [Rectangle](./rectangle/)() | Constructs a new instance of [Rectangle](./) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Constructs a new instance of [Rectangle](./) object that represents a rectangle with the specified coordinates of its upper left corner and width and height. |
| [Rectangle](./rectangle/)(const Point\&, const Size\&) | Constructs a new instance of [Rectangle](./) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [Point](../point/) class and its width and height as an instance of [Size](../size/) class. |
| [Rectangle](./rectangle/)(const System::Windows::Forms::Screen::Rectangle_\&) | Constructs a new instance of [Rectangle](./) object that represents the rectangle equivalent to the specified one. |
| static [Round](./round/)(const RectangleF\&) | Constructs a [Rectangle](./) object from the specified [RectangleF](../rectanglef/) object by rounding the [RectangleF](../rectanglef/) object's location and size values to the nearest integer values. |
| [set_Height](./set_height/)(int) | Sets the height of the rectangle represented by the current object. |
| [set_Location](./set_location/)(Point) | Sets the location of the upper left corner of the rectangle represented by the current object. |
| [set_Size](./set_size/)(Size) | Sets the width and height of the rectangle represented by the current object. |
| [set_Width](./set_width/)(int) | Sets the width of the rectangle represented by the current object. |
| [set_X](./set_x/)(int) | Sets the X coordinate of the upper left corner of the rectangle represented by the current object. |
| [set_Y](./set_y/)(int) | Sets the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| [ToString](./tostring/)() const | Returns the string representation of the current object. |
| static [Truncate](./truncate/)(const RectangleF\&) | Constructs a [Rectangle](./) object from the specified [RectangleF](../rectanglef/) object by truncating the [RectangleF](../rectanglef/) object's location and size values to the next lower integer values. |
| static [Union](./union/)(const Rectangle\&, const Rectangle\&) | Returns a rectangle that is a result of union of the specified rectangles. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty rectangle i.e. a rectangle whose location and size values have zero values. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
