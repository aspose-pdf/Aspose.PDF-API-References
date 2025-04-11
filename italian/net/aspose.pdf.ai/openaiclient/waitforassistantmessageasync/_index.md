---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Attende il primo messaggio dall'assistente all'interno di un thread in modo asincrono
type: docs
weight: 460
url: /it/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## Metodo OpenAIClient.WaitForAssistantMessageAsync

Attende il primo messaggio dall'assistente all'interno di un thread in modo asincrono.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread da monitorare per il primo messaggio dell'assistente. |
| queryParameters | ThreadMessageListQueryParameters | Parametri di query opzionali per filtrare l'elenco dei messaggi. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene il primo messaggio dell'assistente nel thread.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi Anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)