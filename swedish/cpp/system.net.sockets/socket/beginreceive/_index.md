---
title: "System::Net::Sockets::Socket::BeginReceive metod"
linktitle: "BeginReceive"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::BeginReceive metod. Initierar en asynkron skrivoperation i C++."
type: docs
weight: 800
url: /sv/cpp/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive method


Initierar en asynkron skrivoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | En buffert där den mottagna datan tilldelas. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| size | int32_t | Antalet byte i den angivna arrayen med början från parametern 'offset'. |
| socketFlags | SocketFlags | Mottagningsbeteendet. |
| callback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererad data som används för att unikt identifiera varje asynkron mottagningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona mottagningsoperationen.

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
