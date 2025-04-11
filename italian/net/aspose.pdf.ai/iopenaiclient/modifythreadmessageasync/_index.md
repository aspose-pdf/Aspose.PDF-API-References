---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Modifica un messaggio esistente all'interno di un thread in modo asincrono
type: docs
weight: 390
url: /it/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## Metodo IOpenAIClient.ModifyThreadMessageAsync

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

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica del messaggio.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del messaggio del thread è nullo o vuoto. |

### Vedi anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)