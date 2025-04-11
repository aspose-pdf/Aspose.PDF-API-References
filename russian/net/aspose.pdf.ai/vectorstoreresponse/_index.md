---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.VectorStoreResponse. Объект векторного хранилища
type: docs
weight: 1390
url: /ru/net/aspose.pdf.ai/vectorstoreresponse/
---
## Класс VectorStoreResponse

Объект векторного хранилища.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента создания векторного хранилища. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Получает или задает политику истечения для векторного хранилища. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда векторное хранилище истечет. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Получает или задает количество обработанных файлов. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Получает или задает идентификатор, который можно использовать в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда векторное хранилище было в последний раз активно. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь максимальную длину 64 символа, а значения - максимальную длину 512 символов. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Получает или задает имя векторного хранилища. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Получает или задает статус векторного хранилища, который может быть либо истекшим, в процессе, либо завершенным. Статус завершен указывает на то, что векторное хранилище готово к использованию. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Получает или задает общее количество байтов, использованных файлами в векторном хранилище. |

### См. также

* класс [BaseResponse](../baseresponse/)
* интерфейс [IEntityId](../ientityid/)
* интерфейс [IStatus](../istatus/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)