---
title: "System::Net::Sockets::UdpClient::Send‑metod"
linktitle: "Skicka"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::UdpClient::Send‑metod. Skickar ett UDP‑datagram till en fjärrvärd i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Skickar ett UDP-datagram till en fjärrvärd.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | En array av typen [Byte](../../../system/byte/) att skicka. |
| byte | int32_t | Antalet byte i datagrammet. |

### ReturnValue

Antalet byte som skickas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Skickar ett UDP-datagram till den angivna porten på den angivna fjärrvärden.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | En array av typen [Byte](../../../system/byte/) att skicka |
| byte | int32_t | Antalet byte i datagrammet. |
| värdnamn | String | Ett namn på den fjärranslutna värden. |
| port | int32_t | Ett fjärrportnummer. |

### ReturnValue

Antalet byte som skickas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Skickar ett UDP-datagram till värden vid den fjärranslutna slutpunkten.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | En array av typen [Byte](../../../system/byte/) att skicka |
| byte | int32_t | Antalet byte i datagrammet. |
| endPoint | System::SharedPtr\<IPEndPoint\> | En [IPEndPoint](../../../system.net/ipendpoint/) som representerar värden och porten dit datagrammet ska skickas. |

### ReturnValue

Antalet byte som skickas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
