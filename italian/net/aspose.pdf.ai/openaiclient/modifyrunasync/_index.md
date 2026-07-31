---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Modifica un run esistente all'interno di un thread in modo asincrono"
type: docs
weight: 410
url: /it/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync method

Modifica un'esecuzione esistente all'interno di un thread in modo asincrono.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread che contiene l'esecuzione. |
| runId | String | L'ID del run da modificare. |
| assistantModifyRequest | RunModifyRequest | I dettagli della richiesta per modificare il run. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica del run.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID dell'esecuzione è nullo o vuoto. |

### Vedi anche

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


