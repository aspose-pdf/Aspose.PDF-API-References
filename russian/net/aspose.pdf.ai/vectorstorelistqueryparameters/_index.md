---
title: Class VectorStoreListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.VectorStoreListQueryParameters. Объект параметров запроса для перечисления векторных хранилищ
type: docs
weight: 1360
url: /ru/net/aspose.pdf.ai/vectorstorelistqueryparameters/
---
## Класс VectorStoreListQueryParameters

Объект параметров запроса для перечисления векторных хранилищ.

```csharp
public class VectorStoreListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Конструкторы

| Name | Description |
| --- | --- |
| [VectorStoreListQueryParameters](vectorstorelistqueryparameters/)() | Конструктор по умолчанию. |

## Свойства

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать after=obj_foo для получения следующей страницы списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать before=obj_foo для получения предыдущей страницы списка. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает ограничение на количество объектов, которые будут возвращены. Limit может варьироваться от 1 до 100, а значение по умолчанию - 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по временной метке created_at объектов. asc для восходящего порядка и desc для нисходящего порядка. |

## Методы

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorelistqueryparameters/getqueryparameters/)() | Получает параметры запроса для перечисления векторных хранилищ. |

### См. также

* класс [BaseListQueryParameters](../baselistqueryparameters/)
* интерфейс [IQueryParameters](../iqueryparameters/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)