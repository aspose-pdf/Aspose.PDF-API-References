---
title: System::Net::Sockets::SocketFlags enum
linktitle: SocketFlags
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::SocketFlags enum. Provides constant values for the socket messages in C++.'
type: docs
weight: 1400
url: /cpp/system.net.sockets/socketflags/
---
## SocketFlags enum


Provides constant values for the socket messages.

```cpp
enum class SocketFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | There are no flags used for this call. |
| OutOfBand | 1 | The out-of-band data is being processed. |
| Peek | 2 | Peek at an incoming message. |
| DontRoute | 4 | Send a message without using routing tables. |
| Truncated | 256 | A message is too large to fit into the specified buffer. It has been truncated. |
| ControlDataTruncated | 512 | The control data is greater than 64 KB and doesn't fit into the internal buffer. It has been truncated. |
| Broadcast | 1024 | A broadcast packet. |
| Multicast | 2048 | A multicast packet. |
| Partial | 32768 | A message sent or received partially. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
