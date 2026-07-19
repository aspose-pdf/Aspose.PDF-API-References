---
title: "System::Net::Sockets::NetworkStream::BeginWrite метод"
linktitle: "BeginWrite"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream::BeginWrite метод. Инициирует асинхронную операцию записи в C++."
type: docs
weight: 400
url: /ru/cpp/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite method


Инициирует асинхронную операцию записи.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Буфер, содержащий данные для записи. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для записи. |
| обратный вызов | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| state | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции записи. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию записи.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
