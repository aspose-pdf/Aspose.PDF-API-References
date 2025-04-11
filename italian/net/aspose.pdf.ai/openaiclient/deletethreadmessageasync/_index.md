---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Elimina un messaggio all'interno di un thread in modo asincrono
type: docs
weight: 160
url: /it/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## Metodo OpenAIClient.DeleteThreadMessageAsync

Elimina un messaggio all'interno di un thread in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente il messaggio da eliminare. |
| threadMessageId | String | L'ID del messaggio da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi Anche

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)