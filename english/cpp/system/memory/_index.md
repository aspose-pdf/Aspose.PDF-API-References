---
title: System::Memory class
linktitle: Memory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Memory class. Represents a mutable memory segment backed by an array in C++.'
type: docs
weight: 4700
url: /cpp/system/memory/
---
## Memory class


Represents a mutable memory segment backed by an array.

```cpp
template<typename T>class Memory : public System::Details::MemoryCore<T>
```

## Methods

| Method | Description |
| --- | --- |
| [CopyTo](./copyto/)(const Memory\&) | Copies the contents of this memory to the destination memory. |
| static [get_Empty](./get_empty/)() | Gets an empty [Memory](./) instance. |
| [get_Span](./get_span/)() const | Gets a span that represents the current memory. |
| [operator ReadOnlyMemory< T >](./operatorreadonlymemory_t_/)() const | Implicitly converts [Memory](./) to [ReadOnlyMemory](../readonlymemory/). |
| [Slice](./slice/)(int32_t, int32_t) const | Creates a slice of the current memory. |
| static [to_Memory](./to_memory/)(const ArrayPtr\<T\>\&) | Creates a [Memory](./) instance from the specified array. |
| [ToString](./tostring/)() const | Converts the character memory to a string representation. |
| [ToString](./tostring/)() const | Converts the ordinary memory to a string representation. |
| [TryCopyTo](./trycopyto/)(const Memory\&) | Attempts to copy the contents of this memory to the destination memory. |
## Remarks


Exposes a span over the array region and supports slicing and copying. 
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
