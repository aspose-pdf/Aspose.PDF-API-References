---
title: System::Array::BinarySearch method
linktitle: BinarySearch
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::BinarySearch method. Performs binary search in the sorted array in C++.'
type: docs
weight: 4600
url: /cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Performs binary search in the sorted array.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Sorted array to perform search in |
| item | const T\& | An item to search for |

### ReturnValue

Index of the searched item if one is found, otherwise, a negative integer that is the bitwise complement of the index of the next item greater than searched item or, if there is no greater item, the bitwise complement of the number of elements in the array.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


NOT IMPLEMENTED.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
