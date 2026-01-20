---
title: System::Drawing::Point class
linktitle: Point
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Point class. Represents a pair of integer X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1700
url: /cpp/system.drawing/point/
---
## Point class


Represents a pair of integer X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Point
```

## Methods

| Method | Description |
| --- | --- |
| static [Add](./add/)(const Point\&, const Size\&) | Adds the width and height values of the specified [Size](../size/) object to the X and Y coordinates values of the specified [Point](./) object correspondingly. |
| static [Ceiling](./ceiling/)(const PointF\&) | Constructs a [Point](./) object from the specified [PointF](../pointf/) object by rounding the [PointF](../pointf/) object's X and Y coordinates values to the next higher integer values. |
| [Equals](./equals/)(const Point\&) const | Determines if the current object and the specified object are equal, i.e. represent the same pair of X and Y coordinates values. |
| [get_IsEmpty](./get_isempty/)() const | Determines if both X and Y coordinates values are equal to 0. |
| [get_X](./get_x/)() const | Returns the value of X coordinate represented by the current object. |
| [get_Y](./get_y/)() const | Returns the value of Y coordinate represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [getStdHash](./getstdhash/)() const | Returns a hash value for the current object. |
| [IsNull](./isnull/)() const | Always returns false. |
| [Offset](./offset/)(int, int) | Offsets the X and Y coordinates value represented by the current object by the specified values. |
| [Offset](./offset/)(Point) | Offsets the X and Y coordinates represented by the current object by the values of X and Y coordinates represented by the specified [Point](./) object correspondingly. |
| [operator PointF](./operatorpointf/)() const | Constructs an instance of [PointF](../pointf/) object and initializes it with X and Y coordinates values of the current [Point](./) object. |
| [operator Size](./operatorsize/)() const | Constructs an instance of [Size](../size/) object and initializes its width and height values with X and Y coordinates values represented by the current object correspondingly. |
| [Point](./point/)() | Constructs a new [Point](./) object and initializes its X and Y coordinates values with 0. |
| [Point](./point/)(int, int) | Constructs a new [Point](./) object and initializes it with the specified values. |
| [Point](./point/)(const Size\&) | Constructs a new [Point](./) object and initializes its X and Y coordinates values with the values of width and height of the specifide [SizeF](../sizef/) object correspondingly. |
| [Point](./point/)(int) | Constructs a new [Point](./) object and initializes its X coordinate value with a value formed by high 16 bits of the specified 32-bit integer and its Y coordinate value with a vale formed by low 16 bits of the specified 32-bit integer value value. |
| static [Round](./round/)(const PointF\&) | Constructs a [Point](./) object from the specified [PointF](../pointf/) object by rounding the [PointF](../pointf/) object's X and Y coordinates values to the nearest integer values. |
| [set_X](./set_x/)(int) | Sets the value of X coordinate represented by the current object. |
| [set_Y](./set_y/)(int) | Sets the value of Y coordinate represented by the current object. |
| static [Subtract](./subtract/)(const Point\&, const Size\&) | Subtracts the width and height values of the specified [Size](../size/) object from the X and Y coordinates values of the specified [Point](./) object correspondingly. |
| [ToString](./tostring/)() const | Returns the string representation of the pair of X and Y coordinates values represented by the current object. |
| static [Truncate](./truncate/)(const PointF\&) | Constructs a [Point](./) object from the specified [PointF](../pointf/) object by truncating the [PointF](../pointf/) object's X and Y coordinates values to the next lower integer values. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty instance of [Point](./) class whose X and Y coordinates values are 0. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
