---
title: "IOpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Attende che un messaggio specifico del thread venga completato in modo asincrono"
type: docs
weight: 450
url: /it/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync method

Attende che un messaggio di thread specifico termini in modo asincrono.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread che contiene il messaggio. |
| threadMessageId | String | L'ID del messaggio da monitorare fino al completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato finale del messaggio.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi anche

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


