---
title: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient method"
linktitle: "BeginAcceptTcpClient"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::TcpListener::BeginAcceptTcpClient method. Инициирует асинхронную операцию принятия в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient method


Инициирует асинхронную операцию принятия соединения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | AsyncCallback | Обратный вызов, который будет выполнен, когда операция завершится. |
| state | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции подключения. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/) представляющий инициированную асинхронную операцию принятия.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
