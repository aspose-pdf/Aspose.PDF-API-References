---
title: "Класс RunResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.RunResponse класс. Представляет выполнение запуска в потоке"
type: docs
weight: 1100
url: /ru/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

Представляет запуск выполнения в потоке.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RunResponse](runresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Получает или задает идентификатор помощника, используемого для выполнения этого запуска. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента отмены запуска. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента завершения запуска. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента создания запуска. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента истечения срока действия запуска. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента сбоя запуска. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Получает или задает идентификатор, который может использоваться в конечных точках API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Получает или задает детали, почему запуск неполный. Будет null, если запуск не является неполным. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Получает или задает инструкции, которые помощник использовал для этого запуска. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Получает или задает последнюю ошибку, связанную с этим запуском. Будет null, если ошибок нет. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Получает или задает максимальное количество токенов завершения, указанных как использованные в ходе выполнения запуска. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Получает или задает максимальное количество токенов подсказки, указанных как использованные в ходе выполнения запуска. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Получает или задает модель, которую помощник использовал для этого запуска. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Получает или задает детали действия, необходимого для продолжения запуска. Будет null, если действие не требуется. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Получает или задает формат, который модель должна выводить. Совместим с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo, начиная с gpt-3.5-turbo-1106. Установка значения { \"type\": \"json_object\" } включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является корректным JSON. Важно: при использовании режима JSON вы также должны instruировать модель генерировать JSON самостоятельно через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет лимита токенов, что приводит к длительному и, казалось бы, «застрявшему» запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason=\"length\", что указывает на превышение max_tokens или превышение максимальной длины контекста разговора. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента начала запуска. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Получает или задает статус запуска, который может быть queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete или expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Получает или задает температуру сэмплинга, используемую для этого запуска. Если не задано, по умолчанию 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, на котором выполнялся этот запуск. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Получает или задает, какой (если какой-либо) инструмент вызывается моделью. none означает, что модель не будет вызывать инструменты и вместо этого генерирует сообщение. auto — значение по умолчанию, означающее, что модель может выбирать между генерацией сообщения или вызовом одного или нескольких инструментов. required означает, что модель должна вызвать один или несколько инструментов перед ответом пользователю. Указание конкретного инструмента, например {\"type\": \"file_search\"} или {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}, заставляет модель вызвать этот инструмент. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Получает или задает список инструментов, которые помощник использовал для этого запуска. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Получает или задает значение ядерного сэмплинга, используемое для этого запуска. Если не задано, по умолчанию 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Получает или задает стратегию усечения, которая определяет, как поток будет усечён перед запуском. Используйте это для контроля начального окна контекста запуска. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Получает или задает статистику использования, связанную с запуском. Это значение будет null, если запуск не находится в конечном состоянии (например, in_progress, queued и т.д.). |

### См. также

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


