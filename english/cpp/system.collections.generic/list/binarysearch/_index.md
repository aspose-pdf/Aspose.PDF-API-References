---
title: System::Collections::Generic::List::BinarySearch method
linktitle: BinarySearch
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::List::BinarySearch method. Looks for item in a sorted list in C++.'
type: docs
weight: 800
url: /cpp/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item to look for. |

### ReturnValue

Index of the item in sorted list or complement of closest index.

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item to look for. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../../comparer/) to use. |

### ReturnValue

Index of the item in sorted list or complement of closest index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Range beginning. |
| count | int | Range size. |
| item | const T\& | Item to look for. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../../comparer/) to use. |

### ReturnValue

Index of the item in sorted list or complement of closest index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
