---
title: System::Buffers::IBufferWriter::GetMemory method
linktitle: GetMemory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::IBufferWriter::GetMemory method. Returns a Memory that can be written to, and is guaranteed to have at least sizeHint elements in C++.'
type: docs
weight: 200
url: /cpp/system.buffers/ibufferwriter/getmemory/
---
## IBufferWriter::GetMemory method


Returns a [Memory](../../../system/memory/) that can be written to, and is guaranteed to have at least **sizeHint** elements.

```cpp
virtual System::Memory<T> System::Buffers::IBufferWriter<T>::GetMemory(int32_t sizeHint=0)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Memory](../../../system/memory/) that can be written to.

## See Also

* Class [Memory](../../../system/memory/)
* Class [IBufferWriter](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
