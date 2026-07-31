---
title: "IOpenAIClient.GetAssistantsAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Recupera un elenco di assistenti in modo asincrono"
type: docs
weight: 200
url: /it/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync method

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

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


