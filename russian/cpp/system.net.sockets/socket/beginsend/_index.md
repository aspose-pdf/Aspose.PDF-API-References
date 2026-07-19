---
title: "System::Net::Sockets::Socket::BeginSend метод"
linktitle: "BeginSend"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::BeginSend метод. Инициирует асинхронную операцию отправки в C++."
type: docs
weight: 900
url: /ru/cpp/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend method


Инициирует асинхронную операцию отправки.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Буфер, из которого читаются данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| обратный вызов | AsyncCallback | Обратный вызов, который будет выполнен, когда операция завершится. |
| state | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции отправки. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/) , представляющий инициированную асинхронную операцию отправки.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
