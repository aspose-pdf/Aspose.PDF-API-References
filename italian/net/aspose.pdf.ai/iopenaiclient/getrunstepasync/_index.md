---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera i dettagli di un passaggio specifico all'interno di un'esecuzione in modo asincrono
type: docs
weight: 250
url: /it/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## Metodo IOpenAIClient.GetRunStepAsync

Recupera i dettagli di un passaggio specifico all'interno di un'esecuzione in modo asincrono.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione contenente il passaggio. |
| runStepId | String | L'ID del passaggio dell'esecuzione da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del passaggio dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del passaggio dell'esecuzione è nullo o vuoto. |

### Vedi Anche

* classe [RunStepResponse](../../runstepresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)