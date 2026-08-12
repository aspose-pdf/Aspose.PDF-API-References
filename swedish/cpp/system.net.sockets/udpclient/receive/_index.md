---
title: "System::Net::Sockets::UdpClient::Receive‑metod"
linktitle: "Mottag"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::UdpClient::Receive‑metod. Returnerar ett datagram som skickats av en server i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive method


Returnerar ett datagram som skickats av en server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | System::SharedPtr\<IPEndPoint\>\& | En [IPEndPoint](../../../system.net/ipendpoint/) som representerar fjärrvärden som datan skickades från. |

### ReturnValue

En byte‑array där mottagna data kommer att tilldelas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
