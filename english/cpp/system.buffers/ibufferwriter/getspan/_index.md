---
title: System::Buffers::IBufferWriter::GetSpan method
linktitle: GetSpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::IBufferWriter::GetSpan method. Returns a Span that can be written to, and is guaranteed to have at least sizeHint elements in C++.'
type: docs
weight: 300
url: /cpp/system.buffers/ibufferwriter/getspan/
---
## IBufferWriter::GetSpan method


Returns a [Span](../../../system/span/) that can be written to, and is guaranteed to have at least **sizeHint** elements.

```cpp
virtual System::Span<T> System::Buffers::IBufferWriter<T>::GetSpan(int32_t sizeHint=0)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Span](../../../system/span/) that can be written to.

## See Also

* Class [Span](../../../system/span/)
* Class [IBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
