---
title: System::IO::BinaryWriter::Seek method
linktitle: Seek
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryWriter::Seek method. Sets the position of the stream represented by the current object in C++.'
type: docs
weight: 700
url: /cpp/system.io/binarywriter/seek/
---
## BinaryWriter::Seek method


Sets the position of the stream represented by the current object.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int | The byte offset relative to a position specified by **origin** |
| origin | System::IO::SeekOrigin | Specifies the position from which and the direction toward which the offset is calculated |

### ReturnValue

The new position of the stream

## See Also

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
