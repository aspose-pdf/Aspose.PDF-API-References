---
title: "Класс BaseListQueryParameters"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.BaseListQueryParameters. Базовые параметры запроса для перечисления объектов"
type: docs
weight: 160
url: /ru/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters class

Базовые параметры запроса для получения списка объектов.

```csharp
public class BaseListQueryParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать after=obj_foo, чтобы получить следующую страницу списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать before=obj_foo, чтобы получить предыдущую страницу списка. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает ограничение на количество возвращаемых объектов. Ограничение может быть от 1 до 100, значение по умолчанию — 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по метке времени created_at объектов. asc — для сортировки по возрастанию, desc — для сортировки по убыванию. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


