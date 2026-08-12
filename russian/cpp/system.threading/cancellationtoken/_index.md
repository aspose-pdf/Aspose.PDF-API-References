---
title: "System::Threading::CancellationToken class"
linktitle: "CancellationToken"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::CancellationToken class. Распространяет уведомление о том, что операции должны быть отменены. Этот класс предоставляет механизм кооперативной отмены между потоками, позволяя одному потоку уведомлять другие, что операция должна быть отменена в C++."
type: docs
weight: 200
url: /ru/cpp/system.threading/cancellationtoken/
---
## CancellationToken class


Распространяет уведомление о том, что операции должны быть отменены. Этот класс предоставляет механизм кооперативной отмены между потоками, позволяя одному потоку уведомлять другие о необходимости отмены операции.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Методы

| Метод | Описание |
| --- | --- |
| [CancellationToken](./cancellationtoken/)() | Конструктор по умолчанию. |
| [get_CanBeCanceled](./get_canbecanceled/)() const | Определяет, может ли этот токен находиться в состоянии отмены. |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Определяет, был ли запрошен отказ от отмены для данного токена. |
| static [get_None](./get_none/)() | Возвращает пустое значение [System::Threading::CancellationToken](./). |
| [Register](./register/)(const Action<>\&) const | Регистрирует обратный вызов, который будет выполнен при запросе отмены. |
| [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Выбрасывает OperationCanceledException, если отмена была запрошена. |
## Примечания



Токен [CancellationToken](./) может быть отменён только через связанный [CancellationTokenSource](../cancellationtokensource/).

## См. также

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
