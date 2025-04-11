---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera un elenco di passaggi per un'esecuzione specifica all'interno di un thread in modo asincrono
type: docs
weight: 260
url: /it/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## Metodo IOpenAIClient.GetRunStepsAsync

Recupera un elenco di passaggi per un'esecuzione specifica all'interno di un thread in modo asincrono.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione da cui recuperare i passaggi. |
| queryParameters | RunStepListQueryParameters | Parametri di query facoltativi per filtrare l'elenco dei passaggi dell'esecuzione. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene l'elenco dei passaggi dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi anche

* classe [RunStepListResponse](../../runsteplistresponse/)
* classe [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)