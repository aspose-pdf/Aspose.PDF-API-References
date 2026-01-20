---
title: System::Net::Sockets::TcpListener::BeginAcceptTcpClient method
linktitle: BeginAcceptTcpClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::TcpListener::BeginAcceptTcpClient method. Initiates an asynchronous accept operation in C++.'
type: docs
weight: 600
url: /cpp/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient method


Initiates an asynchronous accept operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | AsyncCallback | A callback that will be called when the operation completes. |
| state | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous connect operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous accept operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
