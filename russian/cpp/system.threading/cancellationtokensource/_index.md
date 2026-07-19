---
title: "System::Threading::CancellationTokenSource class"
linktitle: "CancellationTokenSource"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::CancellationTokenSource class. Источник токена отмены, который можно использовать для инициирования уведомлений об отмене в C++."
type: docs
weight: 400
url: /ru/cpp/system.threading/cancellationtokensource/
---
## CancellationTokenSource class


Источник токена отмены, который может использоваться для инициирования уведомлений об отмене.

```cpp
class CancellationTokenSource : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Cancel](./cancel/)() | Сообщает запрос на отмену. |
| [CancellationTokenSource](./cancellationtokensource/)() | Создаёт новый [CancellationTokenSource](./). |
| static [CreateLinkedTokenSource](./createlinkedtokensource/)(const CancellationToken\&, const CancellationToken\&) | Создаёт связанный источник токенов, который отменяется, когда любой из предоставленных токенов отменяется. |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые [CancellationTokenSource](./). |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Получает, была ли запрошена отмена. |
| [get_Token](./get_token/)() const | Получает токен отмены, связанный с этим источником. |
## Примечания


Предоставляет механизмы создания и управления токенами отмены для кооперативной отмены операций.
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
