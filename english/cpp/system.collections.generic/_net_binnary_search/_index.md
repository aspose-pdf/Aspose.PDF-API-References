---
title: System::Collections::Generic::_net_binnary_search method
linktitle: _net_binnary_search
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::_net_binnary_search method. Implements binary search in random access container. Specialization for smart pointers. Uses System::Object::CompareTo method in C++.'
type: docs
weight: 4900
url: /cpp/system.collections.generic/_net_binnary_search/
---
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implements binary search in random access container. Specialization for smart pointers. Uses System::Object::CompareTo method.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<IsSmartPtr<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Description |
| --- | --- |
| containerT | STL-styled container template type with two template arguments: element type and allocator type. |
| T | Element type. |
| Allocator | Allocator type. |

| Parameter | Type | Description |
| --- | --- | --- |
| container | const containterT\<T, Allocator\>\& | Container to search in. |
| index | int | Search range beginning index. |
| count | int | Search range length. |
| value | T | Value to look for. |

### ReturnValue

If found, index of the next element; otherwise, complements of index at which the search stopped.

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implements binary search in random access container. Specialization for value types. Uses CompareTo method.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Description |
| --- | --- |
| containerT | STL-styled container template type with two template arguments: element type and allocator type. |
| T | Element type. |
| Allocator | Allocator type. |

| Parameter | Type | Description |
| --- | --- | --- |
| container | const containterT\<T, Allocator\>\& | Container to search in. |
| index | int | Search range beginning index. |
| count | int | Search range length. |
| value | T | Value to look for. |

### ReturnValue

If found, index of the next element; otherwise, complements of index at which the search stopped.

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implements binary search in random access container. Specialization for scalar types. Compares elements using greater and less operators.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Description |
| --- | --- |
| containerT | STL-styled container template type with two template arguments: element type and allocator type. |
| T | Element type. |
| Allocator | Allocator type. |

| Parameter | Type | Description |
| --- | --- | --- |
| container | const containterT\<T, Allocator\>\& | Container to search in. |
| index | int | Search range beginning index. |
| count | int | Search range length. |
| value | T | Value to look for. |

### ReturnValue

If found, index of the next element; otherwise, complements of index at which the search stopped.

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Implements binary search in random access container.

```cpp
template<template< typename, typename > class,class T,class Allocator> int System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer)
```


| Parameter | Description |
| --- | --- |
| containerT | STL-styled container template type with two template arguments: element type and allocator type. |
| T | Element type. |
| Allocator | Allocator type. |

| Parameter | Type | Description |
| --- | --- | --- |
| container | const containterT\<T, Allocator\>\& | Container to search in. |
| index | int | Search range beginning index. |
| count | int | Search range length. |
| value | T | Value to look for. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../comparer/) object. |

### ReturnValue

If found, index of the next element; otherwise, complements of index at which the search stopped.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
