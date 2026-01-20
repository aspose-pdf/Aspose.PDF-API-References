---
title: System::Array::Sort method
linktitle: Sort
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Sort method. Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using operator< in C++.'
type: docs
weight: 5800
url: /cpp/system/array/sort/
---
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


| Parameter | Description |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

| Parameter | Type | Description |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) that contains key values |
| items | const ArrayPtr\<TValue\>\& | [Array](../) that contains items that are mapped to the key values in **keys** array |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using default comparer.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


| Parameter | Description |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

| Parameter | Type | Description |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) that contains key values |
| items | const ArrayPtr\<TValue\>\& | [Array](../) that contains items that are mapped to the key values in **keys** array |
| index | int | The index designating the beginning of the range to sort |
| length | int | The number of elements in the range to sort |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&) method


Sorts elements in the specified array using default comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Targed array |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorts elements in the specified array using specified comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Targed array |
| comparator | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | IComparer<T> object used to compare elements of the array |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


NOT IMPLEMENTED.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Sorts a range of elements in the specified array using default comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Targed array |
| startIndex | int | The index designating the beginning of the range of elements to sort |
| count | int | The size of the range of elements to sort |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
