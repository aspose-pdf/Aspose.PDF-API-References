---
title: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient metod"
linktitle: "BeginAcceptTcpClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient metod. Initierar en asynkron accepteringsoperation i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient method


Initierar en asynkron accept-operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
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
