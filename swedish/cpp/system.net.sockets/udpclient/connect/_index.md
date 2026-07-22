---
title: "System::Net::Sockets::UdpClient::Connect method"
linktitle: "Connect"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::UdpClient::Connect method. Upprättar en anslutning till den angivna porten på den angivna värden i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Upprättar en anslutning till den angivna porten på den angivna värden.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värdnamn | String | Namnet på den fjärranslutna DNS-värden som du avser att ansluta till. |
| port | int32_t | Det lokala portnumret från vilket du avser att kommunicera. |

## Se även

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Upprättar en anslutning med värden på den angivna adressen på den angivna porten.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addr | System::SharedPtr\<IPAddress\> | Den [IPAddress](../../../system.net/ipaddress/) för den fjärranslutna värden som data ska skickas till. |
| port | int32_t | Det lokala portnumret från vilket du avser att kommunicera. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Upprättar en anslutning till en fjärrslutpunkt.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slutpunkt | System::SharedPtr\<IPEndPoint\> | slutpunkten som du binder UDP-anslutningen till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
