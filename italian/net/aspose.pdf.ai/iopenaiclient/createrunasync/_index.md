---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un run all'interno di un thread specificato in modo asincrono
type: docs
weight: 50
url: /it/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## Metodo IOpenAIClient.CreateRunAsync

Crea un run all'interno di un thread specificato in modo asincrono.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread in cui verrà creato il run. |
| runCreateRequest | RunCreateRequest | I dettagli della richiesta per creare il run. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del run.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi Anche

* classe [RunResponse](../../runresponse/)
* classe [RunCreateRequest](../../runcreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)