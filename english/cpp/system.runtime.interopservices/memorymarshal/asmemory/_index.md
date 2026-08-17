---
title: System::Runtime::InteropServices::MemoryMarshal::AsMemory method
linktitle: AsMemory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::InteropServices::MemoryMarshal::AsMemory method. Casts a ReadOnlyMemory to mutable Memory in C++.'
type: docs
weight: 200
url: /cpp/system.runtime.interopservices/memorymarshal/asmemory/
---
## MemoryMarshal::AsMemory method


Casts a [ReadOnlyMemory](../../../system/readonlymemory/) to mutable [Memory](../../../system/memory/).

```cpp
template<typename T> static Memory<T> System::Runtime::InteropServices::MemoryMarshal::AsMemory(const ReadOnlyMemory<T> &memory)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the [ReadOnlyMemory](../../../system/readonlymemory/). |

| Parameter | Type | Description |
| --- | --- | --- |
| memory | const ReadOnlyMemory\<T\>\& | The [ReadOnlyMemory](../../../system/readonlymemory/) to cast. |

### ReturnValue

A [Memory](../../../system/memory/) object that represents the same memory as the [ReadOnlyMemory](../../../system/readonlymemory/).

## See Also

* Class [Memory](../../../system/memory/)
* Class [ReadOnlyMemory](../../../system/readonlymemory/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
