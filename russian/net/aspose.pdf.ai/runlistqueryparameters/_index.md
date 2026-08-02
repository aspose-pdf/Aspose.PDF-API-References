---
title: "Класс RunListQueryParameters"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.RunListQueryParameters. Объект параметров запроса для перечисления запусков"
type: docs
weight: 1070
url: /ru/net/aspose.pdf.ai/runlistqueryparameters/
---
## RunListQueryParameters class

Объект параметров запроса для перечисления выполнений.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать after=obj_foo, чтобы получить следующую страницу списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before — это идентификатор объекта, определяющий ваше положение в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивая obj_foo, ваш последующий вызов может включать before=obj_foo, чтобы получить предыдущую страницу списка. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает ограничение на количество возвращаемых объектов. Ограничение может быть от 1 до 100, значение по умолчанию — 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по метке времени created_at объектов. asc — для сортировки по возрастанию, desc — для сортировки по убыванию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Получает параметры запроса для перечисления запусков. |

### См. также

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


