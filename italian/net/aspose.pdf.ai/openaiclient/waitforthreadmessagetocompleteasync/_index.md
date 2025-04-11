---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Attende che un messaggio di thread specifico venga completato in modo asincrono
type: docs
weight: 480
url: /it/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## Metodo OpenAIClient.WaitForThreadMessageToCompleteAsync

Attende che un messaggio di thread specifico venga completato in modo asincrono.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente il messaggio. |
| threadMessageId | String | L'ID del messaggio da monitorare fino al completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato finale del messaggio.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi Anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)