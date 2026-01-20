---
title: System::Drawing::SizeF class
linktitle: SizeF
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::SizeF class. Represents a pair of single-precision floating point values that represent width and height of an image. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 2300
url: /cpp/system.drawing/sizef/
---
## SizeF class


Represents a pair of single-precision floating point values that represent width and height of an image. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class SizeF
```

## Methods

| Method | Description |
| --- | --- |
| static [Add](./add/)(const SizeF\&, const SizeF\&) | Returns a new [SizeF](./) object that is a sum of the specified [SizeF](./) objects, i.e. whose width value is equal to the sum of width values of the specified objects and height value is equal to the sum of height values of the specified objects. |
| [Equals](./equals/)(const SizeF\&) const | Determines if the current object and the specified object are equal, i.e. represent the same pair of width and hegiht values. |
| [get_Height](./get_height/)() const | Returns the value of height represented by the current object. |
| [get_IsEmpty](./get_isempty/)() const | Determines if both width and hegiht values are equal to 0. |
| [get_Width](./get_width/)() const | Returns the value of width represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [operator PointF](./operatorpointf/)() const | Converts the current object to an instance of [Point](../point/) object by initializing its X and Y coordinate with the current object's width and height values correspondingly. |
| [operator+=](./operator+=/)(const SizeF\&) | Adds the specified [SizeF](./) object's width and height values to the width and height values of the current [SizeF](./) object correspondingly. |
| [set_Height](./set_height/)(float) | Sets the value of height represented by the current object. |
| [set_Width](./set_width/)(float) | Sets the value of width represented by the current object. |
| [SizeF](./sizef/)() | Constructs a new [SizeF](./) object and initializes its width and height values with 0. |
| [SizeF](./sizef/)(const PointF\&) | Constructs a new [SizeF](./) object and initializes its width and height values with the values of X and Y coordinates of the specifide point correspondingly. |
| [SizeF](./sizef/)(float, float) | Constructs a new [SizeF](./) object and initializes it with the specified value. |
| static [Subtract](./subtract/)(const SizeF\&, const SizeF\&) | Returns a new [SizeF](./) object that is the results of subctraction of **size2** from **size1**, i.e. whose width value is the result of subtraction of **size2's** width value from **size1's** width value and height value is the result of subtraction of **size2's** height value from **size1's** height value. |
| [ToPointF](./topointf/)() const | Converts the current object to an instance of [Point](../point/) object by initializing its X and Y coordinate with the current object's width and height values correspondingly. |
| [ToSize](./tosize/)() const | Constructs a [Size](../size/) object from the current [SizeF](./) object by truncating the [SizeF](./) object's width and height values to the next lower integer values. |
| [ToString](./tostring/)() const | Returns the string representation of the pair of width and hegiht values represented by the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty instance of [SizeF](./) class whose width and height values are 0. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
