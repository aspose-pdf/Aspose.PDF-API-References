---
title: System::Array::FindAll method
linktitle: FindAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::FindAll method. Retrieves all the elements that match the conditions defined by the specified predicate in C++.'
type: docs
weight: 5200
url: /cpp/system/array/findall/
---
## Array::FindAll method


Retrieves all the elements that match the conditions defined by the specified predicate.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) to search an elements in |
| match | System::Predicate\<T\> | A predicate that defines the conditions to match array elements against |

### ReturnValue

An [Array](../) containing all the elements that match the conditions defined by the specified predicate, if found; otherwise, an empty [Array](../).

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
