---
title: "Класс ThreadMessageResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.ThreadMessageResponse. Представляет сообщение в потоке."
type: docs
weight: 1250
url: /ru/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

Представляет сообщение в ветке.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Получает или задает, при необходимости, идентификатор помощника, создавшего это сообщение. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Получает или задает список файлов, прикреплённых к сообщению. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента завершения сообщения. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Получает или задает содержимое сообщения в виде массива текста и/или изображений. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента создания сообщения. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Получает или задает идентификатор, который может использоваться в конечных точках API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента, когда сообщение было помечено как неполное. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Получает или задает неполное сообщение, детали о том, почему сообщение неполное. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Получает или задает сущность, создавшую сообщение. Одно из значений: "user" или "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Получает или задает идентификатор выполнения, связанный с созданием этого сообщения. Значение равно null, когда сообщения создаются вручную. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Получает или задает статус сообщения. Одно из значений: queued, in_progress, requires_action или completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, к которому относится это сообщение. |

### См. также

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


