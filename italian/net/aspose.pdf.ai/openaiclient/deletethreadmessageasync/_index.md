---
title: "OpenAIClient.DeleteThreadMessageAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Elimina un messaggio all'interno di un thread in modo asincrono"
type: docs
weight: 160
url: /it/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync method

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

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi anche

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


