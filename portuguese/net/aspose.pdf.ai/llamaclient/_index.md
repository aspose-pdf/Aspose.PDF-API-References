---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaClient. Representa um cliente para interagir com a API Llama
type: docs
weight: 700
url: /pt/net/aspose.pdf.ai/llamaclient/
---
## Classe LlamaClient

Representa um cliente para interagir com a API Llama.

Representa um cliente para interagir com a API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtém ou define o atraso de retrocesso em segundos. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtém ou define o número máximo de tentativas de requisições HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtém ou define o intervalo de polling em segundos. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtém ou define o tempo limite de polling em segundos. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Cria uma solicitação de conclusão de chat no serviço Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Desfaz os recursos usados pelo [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Obtém uma instância de [`ISummaryCopilot`](../isummarycopilot/) com as opções especificadas. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Cria uma nova instância de [`Builder`](../llamaclient.builder/) com a chave da API fornecida. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Classe Builder para criar uma instância de `LlamaClient`. |

### Veja Também

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)