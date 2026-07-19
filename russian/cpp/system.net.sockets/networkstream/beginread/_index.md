---
title: "System::Net::Sockets::NetworkStream::BeginRead метод"
linktitle: "BeginRead"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream::BeginRead метод. Инициирует асинхронную операцию чтения в C++."
type: docs
weight: 300
url: /ru/cpp/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead method


Инициирует асинхронную операцию чтения.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны прочитанные байты. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для чтения. |
| обратный вызов | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| state | System::SharedPtr\<Object\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции чтения. |

### ReturnValue

[IAsyncResult](../../../system/iasyncresult/) объект, представляющий инициированную асинхронную операцию чтения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
