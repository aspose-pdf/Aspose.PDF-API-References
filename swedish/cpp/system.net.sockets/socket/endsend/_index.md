---
title: "System::Net::Sockets::Socket::EndSend metod"
linktitle: "EndSend"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::EndSend metod. Väntar tills den angivna asynkrona sändningsoperationen slutförs i C++."
type: docs
weight: 1600
url: /sv/cpp/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Väntar tills den angivna asynkrona sändningsoperationen är klar.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron sändningsoperation. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Väntar tills den angivna asynkrona sändningsoperationen är klar.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron sändningsoperation. |
| errorCode | SocketError\& | Utdata‑parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### ReturnValue

Antalet skickade byte.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
