---
title: System::Array::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::CopyTo method. Copies all elements of the current array to the specified destination array. Elements are inserted into destination array starting at index specified by arrayIndex argument in C++.'
type: docs
weight: 900
url: /cpp/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) method


Copies all elements of the current array to the specified destination array. Elements are inserted into destination array starting at index specified by arrayIndex argument.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Destination array |
| arrayIndex | int | Index in destination array to start inserting copied items at |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const method


Copies all elements of the current array to the specified destination array. Elements are inserted into the destination array starting at index specified by dstIndex argument.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


| Parameter | Description |
| --- | --- |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copies a specified number of elements from the current array starting at specified position to specified destination array. Elements are inserted into the destination array starting at index specified by dstIndex argument.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parameter | Description |
| --- | --- |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| srcIndex | int64_t | Index in source array to start copying items at |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |
| count | int64_t | Number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const method


Copies all elements of the current array to the specified destination array view. Elements are inserted into the destination array view starting at index specified by dstIndex argument.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


| Parameter | Description |
| --- | --- |
| DstType | Type of elements in destination array view |

| Parameter | Type | Description |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| dstIndex | int64_t | Index in destination array view to start inserting copied items at |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copies a specified number of elements from the current array starting at specified position to specified destination array view. Elements are inserted into the destination array view starting at index specified by dstIndex argument.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parameter | Description |
| --- | --- |
| DstType | Type of elements in destination array view |

| Parameter | Type | Description |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| srcIndex | int64_t | Index in source array to start copying items at |
| dstIndex | int64_t | Index in destination array view to start inserting copied items at |
| count | int64_t | Number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
