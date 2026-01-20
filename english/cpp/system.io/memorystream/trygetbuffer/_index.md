---
title: System::IO::MemoryStream::TryGetBuffer method
linktitle: TryGetBuffer
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::MemoryStream::TryGetBuffer method. Returns the array of unsigned bytes from which this stream was created in C++.'
type: docs
weight: 1800
url: /cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer method


Returns the array of unsigned bytes from which this stream was created.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArraySegment\<uint8_t\>\& | byte array - out paramter. When this method returns true, the byte array segment from which this stream was created; when this method returns false, this parameter is set to default. |

### ReturnValue

True if the conversion succeeded.

## See Also

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
