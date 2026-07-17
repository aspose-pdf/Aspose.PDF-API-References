---
title: System::Get method
linktitle: Get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Get method. Function to get N-th element of tuple given. Overload for base object in C++.'
type: docs
weight: 21200
url: /cpp/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) method


Function to get N-th element of tuple given. Overload for base object.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


| Parameter | Description |
| --- | --- |
| N | element index. |

| Parameter | Type | Description |
| --- | --- | --- |
| object | const SharedPtr\<Object\>\& | object to inspect. |

### ReturnValue

value of N-th tuple element casted to object.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const SharedPtr\<T\>\&) method


Function to get N-th element of tuple given. Overload for shared pointers.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


| Parameter | Description |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

| Parameter | Type | Description |
| --- | --- | --- |
| object | const SharedPtr\<T\>\& | object to inspect. |

### ReturnValue

value of N-th tuple element.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const T\&) method


Function to get N-th element of tuple given. Overload for objects with Deconstruct method.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


| Parameter | Description |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

| Parameter | Type | Description |
| --- | --- | --- |
| object | const T\& | object to inspect. |

### ReturnValue

value of N-th tuple element.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const ValueTuple\<Args...\>\&) method


Gets N-th element of value tuple.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


| Parameter | Description |
| --- | --- |
| N | element index. |
| Args | tuple elements. |

| Parameter | Type | Description |
| --- | --- | --- |
| tuple | const ValueTuple\<Args...\>\& | tuple to get element from. |

### ReturnValue

value of N-th tuple element.

## See Also

* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Index\&) method


Implementation for collection[index] expressions.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


| Parameter | Description |
| --- | --- |
| T | Collection type. |

| Parameter | Type | Description |
| --- | --- | --- |
| collection | T\& | Collection object. |
| index | const Index\& | Element index of type [System.Index](../index/). |

### ReturnValue

Collection element at the calculated offset.

## See Also

* Class [Index](../index/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Range\&) method


Returns a slice of the specified collection defined by the provided range.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


| Parameter | Type | Description |
| --- | --- | --- |
| collection | T\& | The collection to slice. |
| range | const Range\& | The range specifying the slice boundaries. |

### ReturnValue

A view or slice of the collection from the computed start offset and length.

## See Also

* Class [Range](../range/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
