---
title: System::Net::Sockets::SocketType enum
linktitle: SocketType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::SocketType enum. Enumerates the socket types in C++.'
type: docs
weight: 1800
url: /cpp/system.net.sockets/sockettype/
---
## SocketType enum


Enumerates the socket types.

```cpp
enum class SocketType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Stream | 1 | The type that supports reliable, two-way, connection-based byte streams without duplication of data and without preservation of boundaries. |
| Dgram | 2 | The type that supports datagrams, which are connectionless, unreliable messages of a fixed maximum length. |
| Raw | 3 | The type that supports access to the underlying transport protocol. |
| Rdm | 4 | The type that supports connectionless, message-oriented, reliably delivered messages, and preserves message boundaries in data. |
| Seqpacket | 5 | The type that provides connection-oriented and reliable two-way transfer of ordered byte streams across a network. |
| Unknown | n/a | An unknown type. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
