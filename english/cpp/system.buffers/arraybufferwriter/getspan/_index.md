---
title: System::Buffers::ArrayBufferWriter::GetSpan method
linktitle: GetSpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayBufferWriter::GetSpan method. Returns a Span to write to that is at least the requested length (specified by sizeHint). If no sizeHint is provided (or it''s equal to 0), some non-empty buffer is returned in C++.'
type: docs
weight: 1000
url: /cpp/system.buffers/arraybufferwriter/getspan/
---
## ArrayBufferWriter::GetSpan method


Returns a [Span](../../../system/span/) to write to that is at least the requested length (specified by **sizeHint**). If no **sizeHint** is provided (or it's equal to 0), some non-empty buffer is returned.

```cpp
Span<T> System::Buffers::ArrayBufferWriter<T>::GetSpan(int32_t sizeHint=0) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Span](../../../system/span/) that can be written to.
## Remarks



This will never return an empty [Span](../../../system/span/). 

There is no guarantee that successive calls will return the same buffer or the same-sized buffer. 

You must request a new buffer after calling Advance to continue writing more data and cannot write to a previously acquired buffer. 

## See Also

* Class [Span](../../../system/span/)
* Class [ArrayBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
