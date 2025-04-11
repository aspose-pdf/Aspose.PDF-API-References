---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Modifica un'esecuzione esistente all'interno di un thread in modo asincrono
type: docs
weight: 370
url: /it/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## Metodo IOpenAIClient.ModifyRunAsync

Modifica un'esecuzione esistente all'interno di un thread in modo asincrono.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread contenente l'esecuzione. |
| runId | String | L'ID dell'esecuzione da modificare. |
| assistantModifyRequest | RunModifyRequest | I dettagli della richiesta per modificare l'esecuzione. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica dell'esecuzione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi Anche

* classe [RunResponse](../../runresponse/)
* classe [RunModifyRequest](../../runmodifyrequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)