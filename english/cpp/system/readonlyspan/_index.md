---
title: System::ReadOnlySpan class
linktitle: ReadOnlySpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::ReadOnlySpan class. Forward to use within Span class in C++.'
type: docs
weight: 5300
url: /cpp/system/readonlyspan/
---
## ReadOnlySpan class


Forward to use within [Span](../span/) class.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the span. This class provides a type-safe way to work with contiguous sequences of objects in a read-only manner. It can be used to wrap arrays, stack arrays, or raw pointers while maintaining bounds checking. The [ReadOnlySpan](./) doesn't own the memory it points to - it's just a view into existing memory. |
## Methods

| Method | Description |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const Span\<T\>\&) | Constructs a read-only span from a regular span. |
| static [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Converts an array to a [ReadOnlySpan](./). |
## Remarks


Represents a read-only contiguous region of arbitrary memory.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
