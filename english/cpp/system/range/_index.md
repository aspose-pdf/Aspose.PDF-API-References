---
title: System::Range class
linktitle: Range
second_title: Aspose.PDF for C++ API Reference
description: 'System::Range class. Represents a range with a start and end index. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 5500
url: /cpp/system/range/
---
## Range class


Represents a range with a start and end index. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| static [EndAt](./endat/)(const Index\&) | Creates a range that begins at the start of the collection and ends at the specified end index. |
| [Equals](./equals/)(const Range\&) const | Determines whether the current range is equal to the specified range. |
| static [get_All](./get_all/)() | Returns a [Range](./) that represents the whole collection. |
| [get_End](./get_end/)() const | Gets the End index. |
| [get_Start](./get_start/)() const | Gets the Start index. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current range. |
| [GetOffsetAndLength](./getoffsetandlength/)(int32_t) const | Computes the zero-based start offset and length for the specified collection length. |
| [Range](./range/)() | Constructs an empty range. |
| [Range](./range/)(const Index\&, const Index\&) | Constructs a [Range](./) from the specified start and end indexes. |
| static [StartAt](./startat/)(const Index\&) | Creates a range that begins at the specified start index and extends to the end of the collection. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
