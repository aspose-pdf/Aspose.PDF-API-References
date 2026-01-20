---
title: System::Array::Copy method
linktitle: Copy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Copy method. Copies the specified number of elements from the source array to the destination array in C++.'
type: docs
weight: 4900
url: /cpp/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Copies the specified number of elements from the source array to the destination array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| srcIndex | int64_t | Index in the source array designating the beginning of the range of items to copy |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array view |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| srcIndex | int64_t | Index in the source array designating the beginning of the range of items to copy |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| dstIndex | int64_t | Index in destination array view to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array on stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array on stack |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| srcIndex | int64_t | Index in the source array designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Destination array on stack |
| dstIndex | int64_t | Index in destination array on stack to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method


Copies the specified number of elements from the source array to the destination array view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method


Copies the specified number of elements from the source array to the destination array on stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Destination array on stack |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array on stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array on stack |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Source array view |
| srcIndex | int64_t | Index in the source array view designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| dstIndex | int64_t | Index in destination array on stack to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method


Copies the specified number of elements from the source array view to the destination array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array view |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| srcIndex | int64_t | Index in the source array view designating the beginning of the range of items to copy |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array view |
| DstType | Type of elements in destination array view |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| srcIndex | int64_t | Index in the source array view designating the beginning of the range of items to copy |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| dstIndex | int64_t | Index in destination array view to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method


Copies the specified number of elements from the source array view to the destination array view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| count | int64_t | The number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Copies the specified number of elements from the source array on stack to the destination array.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Source array on stack |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array on stack starting at the specified index to the specified position in destination array.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Source array on stack |
| srcIndex | int64_t | Index in the source array on stack designating the beginning of the range of items to copy |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Copies a specified number of elements from the source array on stack starting at the specified index to the specified position in destination array on stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array on stack |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Source array on stack |
| srcIndex | int64_t | Index in the source array on stack designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| dstIndex | int64_t | Index in destination array on stack to start inserting copied items at |
| count | int64_t | The number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method


Copies the specified number of elements from the source array on stack to the destination array on stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Source array on stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| count | int64_t | The number of elements to copy |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
