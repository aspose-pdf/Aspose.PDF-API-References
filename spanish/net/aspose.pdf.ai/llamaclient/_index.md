---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.LlamaClient. Representa un cliente para interactuar con la API de Llama
type: docs
weight: 700
url: /es/net/aspose.pdf.ai/llamaclient/
---
## Clase LlamaClient

Representa un cliente para interactuar con la API de Llama.

Representa un cliente para interactuar con la API de Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtiene o establece el retraso de retroceso en segundos. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtiene o establece el número máximo de reintentos de solicitudes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtiene o establece el intervalo de sondeo en segundos. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtiene o establece el tiempo de espera de sondeo en segundos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Crea una solicitud de finalización de chat en el servicio Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Libera los recursos utilizados por el [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Obtiene una instancia de [`ISummaryCopilot`](../isummarycopilot/) con las opciones especificadas. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Crea una nueva instancia de [`Builder`](../llamaclient.builder/) con la clave API proporcionada. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Clase Builder para crear una instancia de `LlamaClient`. |

### Véase También

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)