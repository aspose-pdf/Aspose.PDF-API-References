---
title: System::Drawing::PointF class
linktitle: PointF
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::PointF class. Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1800
url: /cpp/system.drawing/pointf/
---
## PointF class


Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class PointF
```

## Methods

| Method | Description |
| --- | --- |
| static [Add](./add/)(const PointF\&, const SizeF\&) | Adds the width and height values of the specified [SizeF](../sizef/) object to the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| static [Add](./add/)(const PointF\&, const Size\&) | Adds the width and height values of the specified [Size](../size/) object to the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| [Equals](./equals/)(const PointF\&) const | Determines if the current object and the specified object are equal, i.e. represent the same pair of X and Y coordinates values. |
| [get_IsEmpty](./get_isempty/)() const | Determines if both X and Y coordinates values are equal to 0. |
| [get_X](./get_x/)() const | Returns the value of X coordinate represented by the current object. |
| [get_Y](./get_y/)() const | Returns the value of Y coordinate represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [IsNull](./isnull/)() const | Always returns false. |
| explicit [operator bool](./operatorbool/)() | Always returns true. |
| [PointF](./pointf/)() | Constructs a new [PointF](./) object and initializes its X and Y coordinates values with 0. |
| [PointF](./pointf/)(float, float) | Constructs a new [PointF](./) object and initializes it with the specified values. |
| [PointF](./pointf/)(const SizeF\&) | Constructs a new [PointF](./) object and initializes its X and Y coordinates values with the values of width and height of the specifide [SizeF](../sizef/) object correspondingly. |
| [set_X](./set_x/)(float) | Sets the value of X coordinate represented by the current object. |
| [set_Y](./set_y/)(float) | Sets the value of Y coordinate represented by the current object. |
| static [Subtract](./subtract/)(const PointF\&, const SizeF\&) | Subtracts the width and height values of the specified [SizeF](../sizef/) object from the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| static [Subtract](./subtract/)(const PointF\&, const Size\&) | Subtracts the width and height values of the specified [Size](../size/) object from the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| [ToString](./tostring/)() const | Returns the string representation of the pair of X and Y coordinates values represented by the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty instance of [PointF](./) class whose X and Y coordinates values are 0. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
