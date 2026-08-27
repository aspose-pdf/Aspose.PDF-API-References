---
title: "Класс ThreadResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.ThreadResponse. Представляет ветку, содержащую сообщения"
type: docs
weight: 1270
url: /ru/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

Представляет ветку, содержащую сообщения.

```csharp
public class ThreadResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) времени создания ветки. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Получает или задает идентификатор, который может использоваться в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Получает или задает набор ресурсов, доступных инструментам ассистента в этой ветке. Ресурсы специфичны для типа инструмента. Например, инструмент code_interpreter требует список ID файлов, тогда как инструмент file_search требует список ID векторных хранилищ. |

### См. также

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


