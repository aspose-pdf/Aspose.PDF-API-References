---
title: "System::Net::Sockets::Socket::BeginSend metod"
linktitle: "BeginSend"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::BeginSend metod. Initierar en asynkron sändningsoperation i C++."
type: docs
weight: 900
url: /sv/cpp/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend method


Initierar en asynkron sändningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | En buffert att läsa data från. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Sändningsbeteendet. |
| callback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron sändningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona sändningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
