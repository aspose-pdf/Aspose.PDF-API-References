---
title: System::IO::MemoryStream::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::MemoryStream::Write method. Writes the specified subrange of bytes from the specified byte array to the stream in C++.'
type: docs
weight: 1900
url: /cpp/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The array containing the bytes to write |
| offset | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The array view containing the bytes to write |
| offset | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
