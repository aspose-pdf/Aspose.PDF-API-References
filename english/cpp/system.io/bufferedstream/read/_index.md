---
title: System::IO::BufferedStream::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BufferedStream::Read method. Reads the specified number of bytes from the underlying stream and writes them to the specified byte array in C++.'
type: docs
weight: 900
url: /cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the underlying stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The byte array to write the read bytes to |
| offset | int32_t | A 0-based position in **buffer** to start writing at |
| count | int32_t | The number of bytes to read |

### ReturnValue

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the underlying stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The byte array to write the read bytes to |
| offset | int32_t | A 0-based position in **buffer** to start writing at |
| count | int32_t | The number of bytes to read |

### ReturnValue

The number of bytes read

## See Also

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
