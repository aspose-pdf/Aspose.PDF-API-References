---
title: System::Buffers::MemoryManager class
linktitle: MemoryManager
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::MemoryManager class. Provides an abstraction for managing memory blocks in C++.'
type: docs
weight: 200
url: /cpp/system.buffers/memorymanager/
---
## MemoryManager class


Provides an abstraction for managing memory blocks.

```cpp
template<typename T>class MemoryManager : public System::IDisposable
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the memory. |
## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the memory manager and releases any resources it holds. |
| virtual [get_Memory](./get_memory/)() | Returns a [Memory<T>](../../system/memory/). |
| virtual [GetSpan](./getspan/)() | Returns a span wrapping the underlying memory. |
| virtual [Pin](./pin/)(int32_t) | Returns a handle to the memory that has been pinned so its address can be taken. |
| virtual [Unpin](./unpin/)() | Indicates the memory can be moved again; unpins previously pinned memory. |

## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
