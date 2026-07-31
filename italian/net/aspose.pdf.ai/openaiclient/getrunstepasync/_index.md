---
title: "OpenAIClient.GetRunStepAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Recupera i dettagli di uno specifico passaggio all'interno di un'esecuzione in modo asincrono"
type: docs
weight: 280
url: /it/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## OpenAIClient.GetRunStepAsync method

Recupera i dettagli di uno step specifico all'interno di un'esecuzione in modo asincrono.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread che contiene l'esecuzione. |
| runId | String | L'ID dell'esecuzione che contiene il passaggio. |
| runStepId | String | L'ID del passaggio dell'esecuzione da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del passaggio dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID dell'esecuzione è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del passaggio dell'esecuzione è nullo o vuoto. |

### Vedi anche

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


