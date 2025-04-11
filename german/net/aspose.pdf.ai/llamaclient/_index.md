---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient-Klasse. Stellt einen Client für die Interaktion mit der Llama-API dar
type: docs
weight: 700
url: /de/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient-Klasse

Stellt einen Client für die Interaktion mit der Llama-API dar.

Stellt einen Client für die Interaktion mit der Llama-API dar.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Ruft die Backoff-Verzögerung in Sekunden ab oder legt sie fest. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Ruft die maximale Anzahl von HTTP-Anforderungswiederholungen ab oder legt sie fest. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Ruft das Abfrageintervall in Sekunden ab oder legt es fest. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Ruft das Abfrage-Timeout in Sekunden ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Erstellt eine Chat-Vervollständigungsanfrage im Llama-Dienst. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Gibt die von [`AIClientBase`](../aiclientbase/) verwendeten Ressourcen frei. |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Ruft eine Instanz von [`ISummaryCopilot`](../isummarycopilot/) mit den angegebenen Optionen ab. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Erstellt eine neue Instanz von [`Builder`](../llamaclient.builder/) mit dem bereitgestellten API-Schlüssel. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Builder-Klasse zum Erstellen einer Instanz von `LlamaClient`. |

### Siehe auch

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)