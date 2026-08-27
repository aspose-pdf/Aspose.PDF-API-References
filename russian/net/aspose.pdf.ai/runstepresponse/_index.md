---
title: "Класс RunStepResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.RunStepResponse. Представляет шаг в выполнении run."
type: docs
weight: 1140
url: /ru/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

Представляет шаг в выполнении run.

```csharp
public class RunStepResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Получает или задает идентификатор ассистента, связанного с шагом выполнения. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента отмены шага выполнения. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента завершения шага выполнения. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента создания шага выполнения. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента истечения срока шага выполнения. Шаг считается истекшим, если родительский run истёк. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента сбоя шага выполнения. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Получает или задает идентификатор шага выполнения, который может использоваться в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Получает или задает последнюю ошибку, связанную с этим шагом выполнения. Будет null, если ошибок нет. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Получает или задает идентификатор выполнения, частью которого является этот шаг выполнения. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Получает или задает тип шага выполнения, который может быть либо message_creation, либо tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Получает или задает статус шага выполнения, который может быть in_progress, cancelled, failed, completed или expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Получает или задает детали шага выполнения. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, который был выполнен. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Получает или задает статистику использования, связанную со шагом выполнения. Это значение будет null, пока статус шага выполнения равен in_progress. |

### См. также

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


