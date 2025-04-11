---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.VectorStoreFileResponse. Ответ на запрос файла векторного хранилища
type: docs
weight: 1350
url: /ru/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Класс VectorStoreFileResponse

Ответ на запрос файла векторного хранилища.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для времени создания файла векторного хранилища. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Получает или задает идентификатор, который может быть использован в конечных точках API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Получает или задает последнюю ошибку, связанную с этим файлом векторного хранилища. Будет равен null, если ошибок нет. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Получает или задает статус файла векторного хранилища, который может быть в процессе, завершен, отменен или неудачен. Статус завершен указывает на то, что файл векторного хранилища готов к использованию. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Получает или задает общий объем использования векторного хранилища в байтах. Обратите внимание, что это может отличаться от исходного размера файла. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Получает или задает идентификатор векторного хранилища, к которому прикреплен файл. |

### См. также

* класс [BaseResponse](../baseresponse/)
* интерфейс [IStatus](../istatus/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)