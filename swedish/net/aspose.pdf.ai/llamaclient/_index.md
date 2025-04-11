---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient klass. Representerar en klient för att interagera med Llama API
type: docs
weight: 700
url: /sv/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient klass

Representerar en klient för att interagera med Llama API.

Representerar en klient för att interagera med Llama API.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Hämtar eller ställer in backoff-fördröjningen i sekunder. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Hämtar eller ställer in det maximala antalet HTTP-förfrågningsåterförsök. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Hämtar eller ställer in pollingintervallet i sekunder. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Hämtar eller ställer in pollingtimeouten i sekunder. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Skapar en chattkompletteringsförfrågan i Llama-tjänsten. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Frigör de resurser som används av [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Hämtar en instans av [`ISummaryCopilot`](../isummarycopilot/) med de angivna alternativen. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Skapar en ny instans av [`Builder`](../llamaclient.builder/) med den angivna API-nyckeln. |

## Andra Medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Builder-klass för att skapa en instans av `LlamaClient`. |

### Se Även

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)