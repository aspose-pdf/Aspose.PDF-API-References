---
title: "System::Net::Security::SslStream::BeginWrite method"
linktitle: "BeginWrite"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::SslStream::BeginWrite method. Инициирует асинхронную операцию записи на C++."
type: docs
weight: 400
url: /ru/cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite method


Инициирует асинхронную операцию записи.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который записываются данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| count | int32_t | Количество байтов для записи. |
| asyncCallback | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| asyncState | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной идентификации каждой асинхронной операции записи. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию записи.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
