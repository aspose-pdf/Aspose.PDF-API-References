---
title: System::Buffers::ArrayPool::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayPool::Create method. Creates a new pool instance with custom configuration options in C++.'
type: docs
weight: 400
url: /cpp/system.buffers/arraypool/create/
---
## ArrayPool::Create method


Creates a new pool instance with custom configuration options.

```cpp
static SharedPtr<ArrayPool<T>> System::Buffers::ArrayPool<T>::Create(int32_t maxArrayLength, int32_t maxArraysPerBucket)
```


| Parameter | Type | Description |
| --- | --- | --- |
| maxArrayLength | int32_t | The maximum array length that may be pooled. |
| maxArraysPerBucket | int32_t | The maximum number of arrays kept in each bucket. |

### ReturnValue

An [ArrayPool](../) with the specified configuration.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ArrayPool](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
