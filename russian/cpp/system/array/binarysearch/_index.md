---
title: "Метод System::Array::BinarySearch"
linktitle: "BinarySearch"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::BinarySearch. Выполняет бинарный поиск в отсортированном массиве в C++."
type: docs
weight: 4800
url: /ru/cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Выполняет бинарный поиск в отсортированном массиве.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Отсортированный массив для выполнения поиска |
| элемент | const T\& | Элемент для поиска |

### ReturnValue

[Index](../../index/) of the searched item if one is found, otherwise, a negative integer that is the bitwise complement of the index of the next item greater than searched item or, if there is no greater item, the bitwise complement of the number of elements in the array.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


НЕ РЕАЛИЗОВАНО.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
