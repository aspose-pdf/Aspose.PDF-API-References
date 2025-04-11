---
title: IOpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Modifica un thread esistente in modo asincrono
type: docs
weight: 380
url: /it/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## Metodo IOpenAIClient.ModifyThreadAsync

Modifica un thread esistente in modo asincrono.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread da modificare. |
| threadModifyRequest | ThreadModifyRequest | L'oggetto di richiesta contenente i dettagli della modifica. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica del thread.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi anche

* classe [ThreadResponse](../../threadresponse/)
* classe [ThreadModifyRequest](../../threadmodifyrequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)