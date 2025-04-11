---
title: IOpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo messaggio all'interno di un thread in modo asincrono
type: docs
weight: 80
url: /it/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## Metodo IOpenAIClient.CreateThreadMessageAsync

Crea un nuovo messaggio all'interno di un thread in modo asincrono.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread in cui verrà creato il messaggio. |
| threadMessageRequest | ThreadMessageCreateRequest | I dettagli della richiesta per creare il messaggio. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del messaggio.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi Anche

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)