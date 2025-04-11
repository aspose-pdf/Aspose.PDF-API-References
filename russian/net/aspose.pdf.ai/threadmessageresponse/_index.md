---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.ThreadMessageResponse. Представляет сообщение в рамках потока
type: docs
weight: 1160
url: /ru/net/aspose.pdf.ai/threadmessageresponse/
---
## Класс ThreadMessageResponse

Представляет сообщение в рамках потока.

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
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Получает или задает, если применимо, идентификатор помощника, который создал это сообщение. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Получает или задает список файлов, прикрепленных к сообщению. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Получает или задает метку времени Unix (в секундах) для момента, когда сообщение было завершено. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Получает или задает содержимое сообщения в виде массива текста и/или изображений. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Получает или задает метку времени Unix (в секундах) для момента, когда сообщение было создано. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Получает или задает идентификатор, который может быть использован в конечных точках API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Получает или задает метку времени Unix (в секундах) для момента, когда сообщение было помечено как неполное. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Получает или задает неполное сообщение, детали о том, почему сообщение неполное. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь длину до 64 символов, а значения — до 512 символов. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Получает или задает сущность, которая создала сообщение. Одна из "user" или "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Получает или задает идентификатор выполнения, связанного с созданием этого сообщения. Значение равно null, когда сообщения создаются вручную. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Получает или задает статус сообщения. Один из queued , in_progress , requires_action , или completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, к которому принадлежит это сообщение. |

### См. также

* класс [BaseResponse](../baseresponse/)
* интерфейс [IStatus](../istatus/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)