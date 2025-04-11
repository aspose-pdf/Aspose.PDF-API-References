---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera un elenco di messaggi per un thread specifico in modo asincrono
type: docs
weight: 290
url: /it/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## Metodo IOpenAIClient.GetThreadMessagesAsync

Recupera un elenco di messaggi per un thread specifico in modo asincrono.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread da cui recuperare i messaggi. |
| queryParameters | ThreadMessageListQueryParameters | Parametri di query opzionali per filtrare l'elenco dei messaggi. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di messaggi del thread.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi anche

* classe [ThreadMessageListResponse](../../threadmessagelistresponse/)
* classe [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)