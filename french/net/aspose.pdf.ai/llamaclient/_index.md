---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaClient. Représente un client pour interagir avec l'API Llama
type: docs
weight: 700
url: /fr/net/aspose.pdf.ai/llamaclient/
---
## Classe LlamaClient

Représente un client pour interagir avec l'API Llama.

Représente un client pour interagir avec l'API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtient ou définit le délai de retour en secondes. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtient ou définit le nombre maximum de tentatives de requêtes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtient ou définit l'intervalle de sondage en secondes. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtient ou définit le délai d'expiration du sondage en secondes. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Crée une demande de complétion de chat dans le service Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Dispose des ressources utilisées par le [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Obtient une instance de [`ISummaryCopilot`](../isummarycopilot/) avec les options spécifiées. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Crée une nouvelle instance de [`Builder`](../llamaclient.builder/) avec la clé API fournie. |

## Autres Membres

| Nom | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Classe Builder pour créer une instance de `LlamaClient`. |

### Voir Aussi

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)