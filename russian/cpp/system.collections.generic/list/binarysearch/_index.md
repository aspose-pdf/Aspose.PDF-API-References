---
title: "System::Collections::Generic::List::BinarySearch method"
linktitle: "BinarySearch"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::List::BinarySearch method. Ищет элемент в отсортированном списке в C++."
type: docs
weight: 800
url: /ru/cpp/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const method


Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const T\& | Элемент для поиска. |

### ReturnValue

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## См. также

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const T\& | Элемент для поиска. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../../comparer/) для использования. |

### ReturnValue

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) начало. |
| count | int | [Range](../../../system/range/) размер. |
| элемент | const T\& | Элемент для поиска. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../../comparer/) для использования. |

### ReturnValue

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
