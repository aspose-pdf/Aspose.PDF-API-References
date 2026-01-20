---
title: System::Buffer::GetByte method
linktitle: GetByte
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffer::GetByte method. Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset in C++.'
type: docs
weight: 300
url: /cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const SharedPtr\<Array\<T\>\>\& | The target array |
| index | int | Zero-based offset of the byte to retrieve |

### ReturnValue

The byte value at the specified index

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | The target array view |
| index | int | Zero-based offset of the byte to retrieve |

### ReturnValue

The byte value at the specified index

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | The target stack array |
| index | int | Zero-based offset of the byte to retrieve |

### ReturnValue

The byte value at the specified index

## See Also

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
