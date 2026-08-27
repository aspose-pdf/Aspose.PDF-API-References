---
title: "IOpenAIClient.GetRunStepsAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "IOpenAIClient metodo. Recupera un elenco di passaggi per un'esecuzione specifica all'interno di un thread in modo asincrono"
type: docs
weight: 260
url: /it/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

Recupera un elenco di step per un'esecuzione specifica all'interno di un thread in modo asincrono.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread che contiene l'esecuzione. |
| runId | String | L'ID dell'esecuzione da cui recuperare i passaggi. |
| queryParameters | RunStepListQueryParameters | Parametri di query opzionali per filtrare l'elenco dei passaggi di esecuzione. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene l'elenco dei passaggi di esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi anche

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


