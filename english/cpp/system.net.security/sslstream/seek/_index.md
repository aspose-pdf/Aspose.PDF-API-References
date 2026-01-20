---
title: System::Net::Security::SslStream::Seek method
linktitle: Seek
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::Seek method. Sets the position of the stream represented by the current object in C++.'
type: docs
weight: 3300
url: /cpp/system.net.security/sslstream/seek/
---
## SslStream::Seek method


Sets the position of the stream represented by the current object.

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | The byte offset relative to a position specified by **origin** |
| origin | IO::SeekOrigin | Specifies the position from which and the direction toward which the offset is calculated |

### ReturnValue

The new position of the stream

## See Also

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
