---
title: Aspose::Pdf::OptimizedMemoryStream::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream::Read method. When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream::Read method


When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

```cpp
int32_t Aspose::Pdf::OptimizedMemoryStream::Read(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | An array of bytes. When this method returns, the buffer contains the specified byte array with the values |
| offset | int32_t | The zero-based byte offset in at which to begin storing the data read from the current stream. |
| count | int32_t | The maximum number of bytes to be read from the current stream. |

### ReturnValue

The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
