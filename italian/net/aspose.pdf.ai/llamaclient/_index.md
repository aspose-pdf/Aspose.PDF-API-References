---
title: "Classe LlamaClient"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.LlamaClient. Rappresenta un client per interagire con l'API Llama"
type: docs
weight: 750
url: /it/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

Rappresenta un client per interagire con l'API Llama.

Rappresenta un client per interagire con l'API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Ottiene o imposta il ritardo di backoff in secondi. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Ottiene o imposta il numero massimo di tentativi di richiesta HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Ottiene o imposta l'intervallo di polling in secondi. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Ottiene o imposta il timeout di polling in secondi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Crea una richiesta di completamento chat nel servizio Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Rilascia le risorse utilizzate da [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Ottiene un'istanza di [`ISummaryCopilot`](../isummarycopilot/) con le opzioni specificate. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Crea una nuova istanza di [`Builder`](../llamaclient.builder/) con la chiave API fornita. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Classe Builder per creare un'istanza di `LlamaClient`. |

### Vedi anche

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


