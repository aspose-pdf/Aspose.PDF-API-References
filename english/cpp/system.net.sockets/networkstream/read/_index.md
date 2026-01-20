---
title: System::Net::Sockets::NetworkStream::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::NetworkStream::Read method. Reads the specified number of bytes from the stream and writes them to the specified byte array in C++.'
type: docs
weight: 1900
url: /cpp/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The byte array where the read bytes will be written. |
| offset | int32_t | The offset in bytes in the specified array. |
| size | int32_t | The number of bytes to read. |

### ReturnValue

The number of read bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The byte array view to write the read bytes to |
| offset | int32_t | A 0-based position in **buffer** to start writing at |
| size | int32_t | The number of bytes to read |

### ReturnValue

The number of bytes read

## See Also

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
