---
title: System::Buffers::SearchValues::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::SearchValues::Create method. Creates a SearchValues instance from the specified set of values in C++.'
type: docs
weight: 300
url: /cpp/system.buffers/searchvalues/create/
---
## SearchValues::Create method


Creates a [SearchValues](../) instance from the specified set of values.

```cpp
static System::SharedPtr<SearchValues<T>> System::Buffers::SearchValues<T>::Create(const ReadOnlySpan<T> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| values | const ReadOnlySpan\<T\>\& | The values to search for. |

### ReturnValue

A [SearchValues](../) instance containing the values.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [SearchValues](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
