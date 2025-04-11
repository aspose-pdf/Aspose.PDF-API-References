---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.RunResponse. Представляет выполнение на потоке
type: docs
weight: 1020
url: /ru/net/aspose.pdf.ai/runresponse/
---
## Класс RunResponse

Представляет выполнение на потоке.

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
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск был отменен. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск был завершен. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск был создан. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск истечет. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск завершился неудачей. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Получает или задает идентификатор, который можно использовать в конечных точках API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Получает или задает детали о том, почему запуск неполный. Будет равен null, если запуск не неполный. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Получает или задает инструкции, которые помощник использовал для этого запуска. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Получает или задает последнюю ошибку, связанную с этим запуском. Будет равен null, если ошибок нет. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Получает или задает максимальное количество токенов завершения, которые, как предполагается, были использованы в ходе запуска. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Получает или задает максимальное количество токенов подсказки, которые, как предполагается, были использованы в ходе запуска. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь максимальную длину 64 символа, а значения - максимальную длину 512 символов. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Получает или задает модель, которую помощник использовал для этого запуска. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Получает или задает детали о действии, необходимом для продолжения запуска. Будет равен null, если действие не требуется. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Получает или задает формат, который модель должна выводить. Совместим с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo с gpt-3.5-turbo-1106. Установка в { "type": "json_object" } включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является допустимым JSON. Важно: при использовании режима JSON вы также должны указать модели, чтобы она сама производила JSON через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет предела токенов, что приведет к длительному и, казалось бы, "застрявшему" запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason="length", что указывает на то, что генерация превысила max_tokens или разговор превысил максимальную длину контекста. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента, когда запуск был начат. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Получает или задает статус запуска, который может быть либо queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete, либо expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Получает или задает температуру выборки, используемую для этого запуска. Если не установлено, по умолчанию равно 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Получает или задает идентификатор потока, который был выполнен в рамках этого запуска. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Получает или задает, какой (если есть) инструмент вызывается моделью. none означает, что модель не будет вызывать никаких инструментов и вместо этого генерирует сообщение. auto - это значение по умолчанию и означает, что модель может выбирать между генерацией сообщения или вызовом одного или нескольких инструментов. required означает, что модель должна вызвать один или несколько инструментов перед ответом пользователю. Указание конкретного инструмента, такого как {"type": "file_search"} или {"type": "function", "function": {"name": "my_function"}} заставляет модель вызвать этот инструмент. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Получает или задает список инструментов, которые помощник использовал для этого запуска. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Получает или задает значение ядерной выборки, используемое для этого запуска. Если не установлено, по умолчанию равно 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Получает или задает стратегию усечения, которая контролирует, как поток будет усечен перед запуском. Используйте это, чтобы контролировать начальное окно контекста запуска. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Получает или задает статистику использования, связанную с запуском. Это значение будет равно null, если запуск не находится в терминальном состоянии (т.е. in_progress, queued и т.д.). |

### См. также

* класс [BaseResponse](../baseresponse/)
* интерфейс [IStatus](../istatus/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)