---
title: System::Buffers::ArrayBufferWriter class
linktitle: ArrayBufferWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayBufferWriter class. Represents a heap-based, array-backed output sink into which data can be written in C++.'
type: docs
weight: 100
url: /cpp/system.buffers/arraybufferwriter/
---
## ArrayBufferWriter class


Represents a heap-based, array-backed output sink into which data can be written.

```cpp
template<typename T>class ArrayBufferWriter : public System::Buffers::IBufferWriter<T>
```


| Parameter | Description |
| --- | --- |
| T | The type of the elements held by the writer. |
## Methods

| Method | Description |
| --- | --- |
| [Advance](./advance/)(int32_t) override | Notifies the writer that **count** amount of data was written to the output Span/Memory. |
| [ArrayBufferWriter](./arraybufferwriter/)() | Creates an instance of an [ArrayBufferWriter](./), in which data can be written to, with the default initial capacity. |
| explicit [ArrayBufferWriter](./arraybufferwriter/)(int32_t) | Creates an instance of an [ArrayBufferWriter](./), in which data can be written to, with an initial capacity specified. |
| [Clear](./clear/)() | Clears the data written to the underlying buffer. |
| [get_Capacity](./get_capacity/)() const | Returns the total amount of space within the underlying buffer. |
| [get_FreeCapacity](./get_freecapacity/)() const | Returns the amount of space available that can still be written into without forcing the underlying buffer to grow. |
| [get_WrittenCount](./get_writtencount/)() const | Returns the amount of data written to the underlying buffer so far. |
| [get_WrittenMemory](./get_writtenmemory/)() const | Returns the data written to the underlying buffer so far, as a [ReadOnlyMemory](../../system/readonlymemory/). |
| [get_WrittenSpan](./get_writtenspan/)() const | Returns the data written to the underlying buffer so far, as a [ReadOnlySpan](../../system/readonlyspan/). |
| [GetMemory](./getmemory/)(int32_t) override | Returns a [Memory](../../system/memory/) to write to that is at least the requested length (specified by **sizeHint**). If no **sizeHint** is provided (or it's equal to 0), some non-empty buffer is returned. |
| [GetSpan](./getspan/)(int32_t) override | Returns a [Span](../../system/span/) to write to that is at least the requested length (specified by **sizeHint**). If no **sizeHint** is provided (or it's equal to 0), some non-empty buffer is returned. |
| [ResetWrittenCount](./resetwrittencount/)() | Resets the data written to the underlying buffer without zeroing its content. |

## See Also

* Class [IBufferWriter](../ibufferwriter/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
