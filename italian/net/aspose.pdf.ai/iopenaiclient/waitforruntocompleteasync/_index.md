---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Attende che un'esecuzione venga completata all'interno di un thread in modo asincrono
type: docs
weight: 440
url: /it/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## Metodo IOpenAIClient.WaitForRunToCompleteAsync

Attende che un'esecuzione venga completata all'interno di un thread in modo asincrono.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione da monitorare fino al completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato finale dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi Anche

* classe [RunResponse](../../runresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)