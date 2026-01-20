---
title: System::IO::BufferedStream::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BufferedStream::Write method. Writes the specified subrange of bytes from the specified byte array to the underlying stream in C++.'
type: docs
weight: 1400
url: /cpp/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the underlying stream.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The array containing the bytes to write |
| offset | int32_t | A 0-based index of the ellemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the underlying stream.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The array containing the bytes to write |
| offset | int32_t | A 0-based index of the ellemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
