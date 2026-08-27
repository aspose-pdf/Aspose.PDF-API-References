---
title: "Classe LlamaClient"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.LlamaClient. Représente un client pour interagir avec l'API Llama"
type: docs
weight: 750
url: /fr/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

Représente un client pour interagir avec l'API Llama.

Représente un client pour interagir avec l'API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtient ou définit le délai de backoff en secondes. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtient ou définit le nombre maximal de nouvelles tentatives de requêtes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtient ou définit l'intervalle d'interrogation en secondes. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtient ou définit le délai d'expiration de l'interrogation en secondes. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Crée une requête de complétion de chat dans le service Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Libère les ressources utilisées par le [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Obtient une instance de [`ISummaryCopilot`](../isummarycopilot/) avec les options spécifiées. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Crée une nouvelle instance de [`Builder`](../llamaclient.builder/) avec la clé API fournie. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Classe Builder pour créer une instance de `LlamaClient`. |

### Voir aussi

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


