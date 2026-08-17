---
title: System::Buffers::MemoryManager::Pin method
linktitle: Pin
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::MemoryManager::Pin method. Returns a handle to the memory that has been pinned so its address can be taken in C++.'
type: docs
weight: 400
url: /cpp/system.buffers/memorymanager/pin/
---
## MemoryManager::Pin method


Returns a handle to the memory that has been pinned so its address can be taken.

```cpp
virtual MemoryHandle System::Buffers::MemoryManager<T>::Pin(int32_t elementIndex=0)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| elementIndex | int32_t | The offset to the element within the memory at which the returned [MemoryHandle](../../memoryhandle/) points. Defaults to 0. |

## See Also

* Class [MemoryHandle](../../memoryhandle/)
* Class [MemoryManager](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
