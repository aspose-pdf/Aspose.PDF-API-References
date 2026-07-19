---
title: "Метод System::Net::Sockets::TcpListener::BeginAcceptSocket"
linktitle: "BeginAcceptSocket"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Sockets::TcpListener::BeginAcceptSocket. Инициирует асинхронную операцию принятия в C++."
type: docs
weight: 500
url: /ru/cpp/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket method


Инициирует асинхронную операцию принятия соединения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
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
