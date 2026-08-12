---
title: "System::Net::Sockets::Socket::EndReceive metod"
linktitle: "EndReceive"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::EndReceive metod. Väntar tills den angivna asynkrona mottagningsoperationen slutförs i C++."
type: docs
weight: 1500
url: /sv/cpp/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Väntar tills den angivna asynkrona mottagningsoperationen är klar.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron mottagningsoperation. |

### ReturnValue

Antalet byte som tas emot.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Väntar tills den angivna asynkrona mottagningsoperationen är klar.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron mottagningsoperation. |
| errorCode | SocketError\& | Den utdataparameter där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### ReturnValue

Antalet mottagna byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
