---
title: "Класс LlamaClient"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.LlamaClient. Представляет клиент для взаимодействия с API Llama"
type: docs
weight: 750
url: /ru/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

Представляет клиент для взаимодействия с API Llama.

Представляет клиент для взаимодействия с API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Получает или задает задержку отката в секундах. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Получает или задает максимальное количество повторных попыток HTTP‑запросов. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Получает или задает интервал опроса в секундах. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Получает или задает тайм‑аут опроса в секундах. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Создаёт запрос завершения чата в сервисе Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Освобождает ресурсы, используемые [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Получает экземпляр [`ISummaryCopilot`](../isummarycopilot/) с указанными параметрами. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Создает новый экземпляр [`Builder`](../llamaclient.builder/) с предоставленным API‑ключом. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Класс Builder для создания экземпляра `LlamaClient`. |

### См. также

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


