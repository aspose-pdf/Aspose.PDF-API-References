---
title: System::Buffer::ByteLength method
linktitle: ByteLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffer::ByteLength method. Determines the number of bytes occupied by all elements of the specified array in C++.'
type: docs
weight: 200
url: /cpp/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const SharedPtr\<Array\<T\>\>\& | An array |

### ReturnValue

The number of bytes occupied by all elements of the specified array

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | An array view |

### ReturnValue

The number of bytes occupied by all elements of the specified array view

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Determines the number of bytes occupied by all elements of the specified array.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | An stack array |

### ReturnValue

The number of bytes occupied by all elements of the specified stack array

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
