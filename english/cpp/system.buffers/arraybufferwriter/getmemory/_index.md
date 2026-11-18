---
title: System::Buffers::ArrayBufferWriter::GetMemory method
linktitle: GetMemory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayBufferWriter::GetMemory method. Returns a Memory to write to that is at least the requested length (specified by sizeHint). If no sizeHint is provided (or it''s equal to 0), some non-empty buffer is returned in C++.'
type: docs
weight: 900
url: /cpp/system.buffers/arraybufferwriter/getmemory/
---
## ArrayBufferWriter::GetMemory method


Returns a [Memory](../../../system/memory/) to write to that is at least the requested length (specified by **sizeHint**). If no **sizeHint** is provided (or it's equal to 0), some non-empty buffer is returned.

```cpp
Memory<T> System::Buffers::ArrayBufferWriter<T>::GetMemory(int32_t sizeHint=0) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Memory](../../../system/memory/) that can be written to.
## Remarks



This will never return an empty [Memory](../../../system/memory/). 

There is no guarantee that successive calls will return the same buffer or the same-sized buffer. 

You must request a new buffer after calling Advance to continue writing more data and cannot write to a previously acquired buffer. 

## See Also

* Class [Memory](../../../system/memory/)
* Class [ArrayBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
