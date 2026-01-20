---
title: System::IO::Stream::Seek method
linktitle: Seek
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream::Seek method. Sets the position of the stream represented by the current object in C++.'
type: docs
weight: 2100
url: /cpp/system.io/stream/seek/
---
## Stream::Seek method


Sets the position of the stream represented by the current object.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | The byte offset relative to a position specified by **origin** |
| origin | SeekOrigin | Specifies the position from which and the direction toward which the offset is calculated |

### ReturnValue

The new position of the stream

## See Also

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
