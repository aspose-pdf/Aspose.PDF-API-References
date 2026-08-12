---
title: "System::IO::Stream::BeginRead метод"
linktitle: "BeginRead"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Stream::BeginRead метод. Инициирует асинхронную операцию чтения в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/stream/beginread/
---
## Stream::BeginRead method


Инициирует асинхронную операцию чтения.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Буфер для чтения |
| смещение | int | 0‑базовое смещение в **buffer**, указывающее позицию, с которой начинать запись прочитанных данных |
| count | int | Количество байтов для чтения |
| обратный вызов | System::AsyncCallback | Обратный вызов, который будет вызван после завершения операции |
| state | System::SharedPtr\<System::Object\> | Пользовательские данные, используемые для уникальной идентификации каждой асинхронной операции чтения |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/) представляющий инициированную асинхронную операцию чтения

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
