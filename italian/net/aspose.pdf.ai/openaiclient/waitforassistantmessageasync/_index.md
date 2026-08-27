---
title: "OpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Attende il primo messaggio dell'assistente all'interno di un thread in modo asincrono"
type: docs
weight: 470
url: /it/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync method

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

### Valore di ritorno

Un task che rappresenta l'operazione asincrona. Il risultato del task contiene il primo messaggio dell'assistente nel thread.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |

### Vedi anche

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


