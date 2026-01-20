---
title: System::Array::FindIndex method
linktitle: FindIndex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::FindIndex method. Searches for the first element in the specified array that satisfies the conditions of the specified predicate in C++.'
type: docs
weight: 5300
url: /cpp/system/array/findindex/
---
## Array::FindIndex method


Searches for the first element in the specified array that satisfies the conditions of the specified predicate.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) to search an element in |
| match | System::Predicate\<T\> | A predicate that defines the conditions to match array elements against |

### ReturnValue

The index of the first element in the array that satisfies the conditions defined by predicate, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
