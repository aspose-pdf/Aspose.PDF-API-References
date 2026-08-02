---
title: "Класс VectorStoreResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.VectorStoreResponse. Объект векторного хранилища"
type: docs
weight: 1480
url: /ru/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

Объект хранилища векторов.

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
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Получает или задает Unix‑таймстамп (в секундах) времени создания векторного хранилища. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Получает или задает политику истечения срока действия для векторного хранилища. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Получает или задает Unix‑таймстамп (в секундах) времени истечения срока действия векторного хранилища. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Получает или задает количество обработанных файлов. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Получает или задает идентификатор, который может использоваться в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Получает или задает Unix‑таймстамп (в секундах) времени последней активности векторного хранилища. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном виде. Ключи могут иметь длину не более 64 символов, а значения — не более 512 символов. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Получает или задает название векторного хранилища. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Получает или задает статус векторного хранилища, который может быть expired, in_progress или completed. Статус completed указывает, что векторное хранилище готово к использованию. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Получает или задает общее количество байтов, используемых файлами во векторном хранилище. |

### См. также

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


