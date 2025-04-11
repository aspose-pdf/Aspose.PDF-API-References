---
title: IOpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera i dettagli di un messaggio specifico all'interno di un thread in modo asincrono
type: docs
weight: 280
url: /it/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## Metodo IOpenAIClient.GetThreadMessageAsync

Recupera i dettagli di un messaggio specifico all'interno di un thread in modo asincrono.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente il messaggio. |
| threadMessageId | String | L'ID del messaggio da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del messaggio del thread.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi Anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)