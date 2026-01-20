---
title: System::Net::Sockets::UdpClient::Receive method
linktitle: Receive
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::UdpClient::Receive method. Returns a datagram sent by a server in C++.'
type: docs
weight: 600
url: /cpp/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive method


Returns a datagram sent by a server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | System::SharedPtr\<IPEndPoint\>\& | An [IPEndPoint](../../../system.net/ipendpoint/) that represents the remote host from which the data was sent. |

### ReturnValue

A byte array where received data will be assigned.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
