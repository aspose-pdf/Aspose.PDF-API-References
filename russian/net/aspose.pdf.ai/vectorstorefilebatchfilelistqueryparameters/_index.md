---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters. Объект параметров запроса для перечисления файлов пакетной обработки векторного хранилища
type: docs
weight: 1290
url: /ru/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## Класс VectorStoreFileBatchFileListQueryParameters

Объект параметров запроса для перечисления файлов пакетной обработки векторного хранилища.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Получает или задает курсор для использования в пагинации. after - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать after=obj_foo, чтобы получить следующую страницу списка. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Получает или задает курсор для использования в пагинации. before - это идентификатор объекта, который определяет ваше место в списке. Например, если вы делаете запрос списка и получаете 100 объектов, заканчивающихся на obj_foo, ваш последующий вызов может включать before=obj_foo, чтобы получить предыдущую страницу списка. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Получает или задает фильтр по статусу файла. Один из in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Получает или задает ограничение на количество объектов, которые будут возвращены. Limit может варьироваться от 1 до 100, а значение по умолчанию - 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Получает или задает порядок сортировки по временной метке created_at объектов. asc для восходящего порядка и desc для нисходящего порядка. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Получает параметры запроса для перечисления файлов пакетной обработки в хранилище. |

### См. также

* класс [BaseListQueryParameters](../baselistqueryparameters/)
* интерфейс [IQueryParameters](../iqueryparameters/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)