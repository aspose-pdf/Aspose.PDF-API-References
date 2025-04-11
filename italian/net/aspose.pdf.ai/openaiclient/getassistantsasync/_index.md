---
title: OpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Recupera un elenco di assistenti in modo asincrono
type: docs
weight: 200
url: /it/net/aspose.pdf.ai/openaiclient/getassistantsasync/
---
## Metodo OpenAIClient.GetAssistantsAsync

Recupera un elenco di assistenti in modo asincrono.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Parametri di query opzionali per filtrare l'elenco degli assistenti. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene l'elenco degli assistenti.

### Vedi anche

* classe [AssistantListResponse](../../assistantlistresponse/)
* classe [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)