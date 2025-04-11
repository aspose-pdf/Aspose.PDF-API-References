---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.FileResponse. Объект FileResponse представляет документ, который был загружен в OpenAI
type: docs
weight: 400
url: /ru/net/aspose.pdf.ai/fileresponse/
---
## Класс FileResponse

Объект FileResponse представляет документ, который был загружен в OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileResponse](fileresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Получает или задает размер файла в байтах. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Получает или задает метку времени Unix (в секундах) для момента создания файла. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Получает или задает имя файла. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Получает или задает идентификатор файла, который можно использовать в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда является файлом. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Получает или задает предполагаемую цель файла. Поддерживаемые значения: assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results и vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |

### См. также

* класс [BaseResponse](../baseresponse/)
* интерфейс [IEntityId](../ientityid/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)