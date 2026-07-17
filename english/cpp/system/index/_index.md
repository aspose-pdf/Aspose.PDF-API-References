---
title: System::Index class
linktitle: Index
second_title: Aspose.PDF for C++ API Reference
description: 'System::Index class. Represents an index into a collection. The index can be from the start or from the end. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 4100
url: /cpp/system/index/
---
## Index class


Represents an index into a collection. The index can be from the start or from the end. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(const Index\&) const | Determines whether the current instance and the specified [Index](./) represent the same position. |
| static [FromEnd](./fromend/)(int32_t) | Creates an [Index](./) that is relative to the end of the collection. |
| static [get_End](./get_end/)() | Gets an [Index](./) object representing the end of a collection. |
| [get_IsFromEnd](./get_isfromend/)() const | Gets a value that indicates whether the index is from the end. |
| static [get_Start](./get_start/)() | Gets an [Index](./) object representing the start of a collection. |
| [get_Value](./get_value/)() const | Gets the index value. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current index. |
| [GetOffset](./getoffset/)(int32_t) const | Converts the current [Index](./) into an offset from the start of a collection with the specified length. |
| [Index](./index/)() | Constructs an instance that represents the start of a collection. |
| [Index](./index/)(int32_t) | Constructs an instance that represents the specified position from the start of a collection. |
| [Index](./index/)(int32_t, bool) | Constructs an instance that represents the specified index. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
