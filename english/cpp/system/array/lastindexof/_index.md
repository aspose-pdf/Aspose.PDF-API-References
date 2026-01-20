---
title: System::Array::LastIndexOf method
linktitle: LastIndexOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::LastIndexOf method. Determines the index of the last occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range in C++.'
type: docs
weight: 5500
url: /cpp/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Determines the index of the last occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const ValueType\& | Item index of which is to be determined |
| startIndex | int | Index at which the search is started |
| count | int | Number of elements of the range to search in |

### ReturnValue

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Determines the index of the last occurrence of the specified item in the array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

| Parameter | Type | Description |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const ValueType\& | Item index of which is to be determined |

### ReturnValue

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Determines the index of the last occurrence of the specified item in the array starting from the specified index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

| Parameter | Type | Description |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const ValueType\& | Item index of which is to be determined |
| startIndex | int | Index at which the search is started |

### ReturnValue

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
