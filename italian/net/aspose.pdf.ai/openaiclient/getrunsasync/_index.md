---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient method. Retrieves a list of runs for a specified thread asynchronously
type: docs
weight: 260
url: /it/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## Metodo OpenAIClient.GetRunsAsync

Recupera un elenco di esecuzioni per un thread specificato in modo asincrono.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread da cui recuperare le esecuzioni. |
| queryParameters | RunListQueryParameters | Parametri di query opzionali per filtrare l'elenco delle esecuzioni. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di esecuzioni.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi Anche

* classe [RunListResponse](../../runlistresponse/)
* classe [RunListQueryParameters](../../runlistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)