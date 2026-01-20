---
title: Aspose::Pdf::OptimizedMemoryStream::Seek method
linktitle: Seek
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream::Seek method. When overridden in a derived class, sets the position within the current stream in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf/optimizedmemorystream/seek/
---
## OptimizedMemoryStream::Seek method


When overridden in a derived class, sets the position within the current stream.

```cpp
int64_t Aspose::Pdf::OptimizedMemoryStream::Seek(int64_t offset, System::IO::SeekOrigin origin) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | A byte offset relative to the *origin*  parameter. |
| origin | System::IO::SeekOrigin | A value of type [T:System::IO::SeekOrigin](../) indicating the reference point used to obtain the new position. |

### ReturnValue

The new position within the current stream.

## See Also

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
