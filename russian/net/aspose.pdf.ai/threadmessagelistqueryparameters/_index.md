---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.ThreadMessageListQueryParameters. Объект параметров запроса для перечисления сообщений в потоке
type: docs
weight: 1130
url: /ru/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## Класс ThreadMessageListQueryParameters

Объект параметров запроса для перечисления сообщений в потоке.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать after=obj_foo, чтобы получить следующую страницу списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать before=obj_foo, чтобы получить предыдущую страницу списка. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает лимит на количество объектов, которые будут возвращены. Limit может варьироваться от 1 до 100, а значение по умолчанию - 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по временной метке created_at объектов. asc для восходящего порядка и desc для нисходящего порядка. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Фильтрует сообщения по идентификатору запуска, который их сгенерировал. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Получает параметры запроса для перечисления сообщений в потоке. |

### См. также

* класс [BaseListQueryParameters](../baselistqueryparameters/)
* интерфейс [IQueryParameters](../iqueryparameters/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)