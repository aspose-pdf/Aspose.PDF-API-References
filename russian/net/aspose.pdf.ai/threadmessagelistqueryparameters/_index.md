---
title: "Класс ThreadMessageListQueryParameters"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.ThreadMessageListQueryParameters класс. Объект параметров запроса для перечисления сообщений потока"
type: docs
weight: 1220
url: /ru/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

Объект параметров запроса для получения списка сообщений ветки.

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
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать after=obj_foo, чтобы получить следующую страницу списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать before=obj_foo, чтобы получить предыдущую страницу списка. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает ограничение на количество возвращаемых объектов. Ограничение может быть от 1 до 100, значение по умолчанию — 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по метке времени created_at объектов. asc — для сортировки по возрастанию, desc — для сортировки по убыванию. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Фильтровать сообщения по идентификатору выполнения, который их сгенерировал. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Получает параметры запроса для перечисления сообщений потока. |

### См. также

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


