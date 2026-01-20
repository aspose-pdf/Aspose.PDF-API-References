---
title: System::Array::Clear method
linktitle: Clear
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Clear method. Not supported because the array represented by the current object is read-only in C++.'
type: docs
weight: 600
url: /cpp/system/array/clear/
---
## Array::Clear() method


Not supported because the array represented by the current object is read-only.

```cpp
virtual void System::Array<T>::Clear() override
```


## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Clear(const ArrayPtr\<Type\>\&, int, int) method


Replaces **count** values starting at the **startIndex** index in the specified array with default values.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Parameter | Description |
| --- | --- |
| Type | Type of elements in the target array |

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Target array |
| startIndex | int | Index at which to start replacing the items |
| count | int | The number of items to replace |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
