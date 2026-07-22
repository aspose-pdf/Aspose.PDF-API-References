---
title: "System::Array::BinarySearch metod"
linktitle: "BinarySearch"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::BinarySearch metod. Utför binärsökning i den sorterade arrayen i C++."
type: docs
weight: 4800
url: /sv/cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Utför binärsökning i den sorterade arrayen.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Sorterad array att utföra sökning i |
| objekt | const T\& | Ett objekt att söka efter |

### ReturnValue

[Index](../../index/) of the searched item if one is found, otherwise, a negative integer that is the bitwise complement of the index of the next item greater than searched item or, if there is no greater item, the bitwise complement of the number of elements in the array.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


INTE IMPLEMENTERAD.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
