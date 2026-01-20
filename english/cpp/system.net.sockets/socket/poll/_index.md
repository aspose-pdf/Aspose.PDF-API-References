---
title: System::Net::Sockets::Socket::Poll method
linktitle: Poll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::Poll method. Returns the status of the socket based on the specified polling mode in C++.'
type: docs
weight: 4200
url: /cpp/system.net.sockets/socket/poll/
---
## Socket::Poll method


Returns the status of the socket based on the specified polling mode.

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| microSeconds | int32_t | The amount of time in milliseconds to wait for a response. |
| mode | SelectMode | The polling mode. |

### ReturnValue

The status of the socket based on the specified polling mode.

## See Also

* Enum [SelectMode](../../selectmode/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
