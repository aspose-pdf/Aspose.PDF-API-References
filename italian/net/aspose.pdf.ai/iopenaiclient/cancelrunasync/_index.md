---
title: "IOpenAIClient.CancelRunAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Annulla un'esecuzione esistente all'interno di un thread in modo asincrono"
type: docs
weight: 10
url: /it/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync method

Annulla in modo asincrono un'esecuzione esistente all'interno di un thread.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread che contiene il run da annullare. |
| runId | String | L'ID del run da annullare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla cancellazione del run.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi anche

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


