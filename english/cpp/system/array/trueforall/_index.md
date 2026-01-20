---
title: System::Array::TrueForAll method
linktitle: TrueForAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::TrueForAll method. Determines whether all elements in the specified array satisfy the conditions defined by specified predicate in C++.'
type: docs
weight: 5900
url: /cpp/system/array/trueforall/
---
## Array::TrueForAll method


Determines whether all elements in the specified array satisfy the conditions defined by specified predicate.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) elements of which to match against the conditions |
| match | System::Predicate\<T\> | A predicate that defines the conditions to match array elements against |

### ReturnValue

true if all elements of the array arr satisfy the conditions defined by predicate match, otherwise false

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
