---
title: "Класс VectorStoreFileResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.VectorStoreFileResponse class. Ответ файла vector store."
type: docs
weight: 1440
url: /ru/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

Ответ файла хранилища векторов.

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
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Получает или задаёт Unix timestamp (в секундах) времени создания файла vector store. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Получает или задаёт идентификатор, который может быть использован в API‑конечных точках. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Получает или задаёт последнюю ошибку, связанную с этим файлом vector store. Будет null, если ошибок нет. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Получает или задаёт тип объекта, который всегда равен vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Получает или задаёт статус файла vector store, который может быть in_progress, completed, cancelled или failed. Статус completed указывает, что файл vector store готов к использованию. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Получает или задаёт общее использование vector store в байтах. Обратите внимание, что это может отличаться от исходного размера файла. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Получает или задает ID векторного хранилища, к которому прикреплен File. |

### См. также

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


