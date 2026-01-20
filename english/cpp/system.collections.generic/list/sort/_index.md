---
title: System::Collections::Generic::List::Sort method
linktitle: Sort
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::List::Sort method. Sorts elements in the list using default comparator in C++.'
type: docs
weight: 4400
url: /cpp/system.collections.generic/list/sort/
---
## List::Sort() method


Sorts elements in the list using default comparator.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(Comparison\<T\>, bool) method


Sorts elements in the list.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


| Parameter | Type | Description |
| --- | --- | --- |
| comparison | Comparison\<T\> | [Comparison](../../../system/comparison/) to use. |

## See Also

* Class [Comparison](../../../system/comparison/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorts elements in the list.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| comparator | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Comparator to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) method


Sorts elements in the list slice.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Slice beginning index. |
| count | int | Slice size. |
| comparator | SharedPtr\<System::Collections::Generic::IComparer\<T\>\> | Comparator to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
