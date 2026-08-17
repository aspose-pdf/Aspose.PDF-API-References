---
title: System::ReadOnlyMemory class
linktitle: ReadOnlyMemory
second_title: Aspose.PDF for C++ API Reference
description: 'System::ReadOnlyMemory class. Represents a read-only memory segment backed by an array in C++.'
type: docs
weight: 5700
url: /cpp/system/readonlymemory/
---
## ReadOnlyMemory class


Represents a read-only memory segment backed by an array.

```cpp
template<typename T>class ReadOnlyMemory : public System::Details::MemoryCore<T>
```

## Methods

| Method | Description |
| --- | --- |
| static [get_Empty](./get_empty/)() | Gets an empty [ReadOnlyMemory](./) instance. |
| [get_Span](./get_span/)() const | Gets a read-only span that represents the current memory. |
| [Slice](./slice/)(int32_t, int32_t) const | Creates a slice of the current readonly memory. |
| static [to_ReadOnlyMemory](./to_readonlymemory/)(const ArrayPtr\<T\>\&) | Creates a [ReadOnlyMemory](./) instance from the specified array. |
| [ToString](./tostring/)() const | Converts the character read-only memory to a string representation. |
| [ToString](./tostring/)() const | Converts the ordinary read-only memory to a string representation. |
## Remarks


Exposes a read-only span over the array region and supports slicing. 
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
