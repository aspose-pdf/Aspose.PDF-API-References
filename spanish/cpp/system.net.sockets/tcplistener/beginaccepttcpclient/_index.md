---
title: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient method"
linktitle: "BeginAcceptTcpClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient method. Inicia una operación de aceptación asíncrona en C++."
type: docs
weight: 600
url: /es/cpp/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient method


Inicia una operación de aceptación asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | AsyncCallback | Una callback que será llamada cuando la operación se complete. |
| state | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de conexión asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de aceptación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
