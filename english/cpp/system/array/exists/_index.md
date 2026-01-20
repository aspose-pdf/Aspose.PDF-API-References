---
title: System::Array::Exists method
linktitle: Exists
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Exists method. Determines if the specified Array object contains an element that satisfies requirements of the specified predicate in C++.'
type: docs
weight: 5000
url: /cpp/system/array/exists/
---
## Array::Exists method


Determines if the specified [Array](../) object contains an element that satisfies requirements of the specified predicate.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | The array to look for the element in |
| match | std::function\<bool(T)> | Function object that defines requirements and checks if an element satisfies them |

### ReturnValue

True if **arr** contains an element that satisfies requirements defined by **match**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
