---
title: OpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Recupera i dettagli di un passo specifico all'interno di un'esecuzione in modo asincrono
type: docs
weight: 270
url: /it/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## Metodo OpenAIClient.GetRunStepAsync

Recupera i dettagli di un passo specifico all'interno di un'esecuzione in modo asincrono.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione contenente il passo. |
| runStepId | String | L'ID del passo dell'esecuzione da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del passo dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del passo dell'esecuzione è nullo o vuoto. |

### Vedi Anche

* classe [RunStepResponse](../../runstepresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)