---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Modifica un messaggio esistente all'interno di un thread in modo asincrono
type: docs
weight: 420
url: /it/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## Metodo OpenAIClient.ModifyThreadMessageAsync

Modifica un messaggio esistente all'interno di un thread in modo asincrono.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente il messaggio da modificare. |
| threadMessageId | String | L'ID del messaggio da modificare. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | I dettagli della richiesta per modificare il messaggio. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica del messaggio.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi Anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)