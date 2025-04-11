---
title: OpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Recupera i dettagli di un'esecuzione specifica all'interno di un thread in modo asincrono
type: docs
weight: 250
url: /it/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## Metodo OpenAIClient.GetRunAsync

Recupera i dettagli di un'esecuzione specifica all'interno di un thread in modo asincrono.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi Anche

* classe [RunResponse](../../runresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)