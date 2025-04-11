---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.RunStepResponse. Представляет шаг в выполнении запуска
type: docs
weight: 1060
url: /ru/net/aspose.pdf.ai/runstepresponse/
---
## Класс RunStepResponse

Представляет шаг в выполнении запуска.

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
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Получает или задает идентификатор помощника, связанного с шагом запуска. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда шаг запуска был отменен. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда шаг запуска завершился. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда шаг запуска был создан. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда шаг запуска истек. Шаг считается истекшим, если родительский запуск истек. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда шаг запуска завершился с ошибкой. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Получает или задает идентификатор шага запуска, который может быть использован в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Получает или задает последнюю ошибку, связанную с этим шагом запуска. Будет равен null, если ошибок нет. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь максимальную длину 64 символа, а значения - максимальную длину 512 символов. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Получает или задает идентификатор запуска, частью которого является этот шаг запуска. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Получает или задает тип шага запуска, который может быть либо message_creation, либо tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Получает или задает статус шага запуска, который может быть либо in_progress, либо cancelled, либо failed, либо completed, либо expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Получает или задает детали шага запуска. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, который был запущен. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Получает или задает статистику использования, связанную с шагом запуска. Это значение будет равно null, пока статус шага запуска находится в состоянии in_progress. |

### См. также

* класс [BaseResponse](../baseresponse/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)