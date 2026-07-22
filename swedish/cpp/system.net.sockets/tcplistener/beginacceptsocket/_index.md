---
title: "System::Net::Sockets::TcpListener::BeginAcceptSocket-metoden"
linktitle: "BeginAcceptSocket"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::TcpListener::BeginAcceptSocket-metoden. Initierar en asynkron accept‑operation i C++."
type: docs
weight: 500
url: /sv/cpp/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket method


Initierar en asynkron accept-operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona accepteringsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
