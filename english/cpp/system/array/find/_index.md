---
title: System::Array::Find method
linktitle: Find
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Find method. Searches for the first element in the specified array that satisfies the conditions of the specified predicate in C++.'
type: docs
weight: 5100
url: /cpp/system/array/find/
---
## Array::Find method


Searches for the first element in the specified array that satisfies the conditions of the specified predicate.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) to search an element in |
| match | System::Predicate\<T\> | A predicate that defines the conditions to match array elements against |

### ReturnValue

Copy of the first element in the array that satisfies the conditions defined by predicate, otherwise default value of type T

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
