---
title: System::Buffers::ArrayPool::Return method
linktitle: Return
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayPool::Return method. Returns a previously rented buffer back to the pool in C++.'
type: docs
weight: 300
url: /cpp/system.buffers/arraypool/return/
---
## ArrayPool::Return method


Returns a previously rented buffer back to the pool.

```cpp
void System::Buffers::ArrayPool<T>::Return(const ArrayPtr<T> &array, bool clearArray=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const ArrayPtr\<T\>\& | The buffer obtained previously from [Rent()](../rent/). |
| clearArray | bool | If true, the buffer contents are cleared before pooling. |
## Remarks



Arrays whose length does not match this pool's configuration (e.g. those that were allocated by [Rent()](../rent/) beyond m_maxArrayLength, or come from another pool) are not pooled and are simply released by the reference counting / [GC](../../../system/gc/) mechanism. 

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ArrayPool](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
