---
title: Aspose::Pdf::OptimizedMemoryStream::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream::Write method. When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream::Write method


When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

```cpp
void Aspose::Pdf::OptimizedMemoryStream::Write(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | An array of bytes. This method copies *count*  bytes from *buffer*  to the current stream. |
| offset | int32_t | The zero-based byte offset in *buffer*  at which to begin copying bytes to the current stream. |
| count | int32_t | The number of bytes to be written to the current stream. |
## Remarks



The sum of *offset*  and *count*  is greater than the buffer length. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
