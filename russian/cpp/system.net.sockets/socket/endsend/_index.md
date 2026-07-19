---
title: "System::Net::Sockets::Socket::EndSend метод"
linktitle: "EndSend"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::EndSend метод. Ожидает, пока указанная асинхронная операция отправки не завершится в C++."
type: docs
weight: 1600
url: /ru/cpp/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Ожидает завершения указанной асинхронной операции отправки.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Ожидает завершения указанной асинхронной операции отправки.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию отправки. |
| errorCode | SocketError\& | Выходной параметр, в котором будет присвоен код ошибки, если операция отправки завершится с ошибкой. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
