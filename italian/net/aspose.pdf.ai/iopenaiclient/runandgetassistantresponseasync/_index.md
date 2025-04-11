---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Esegue l'assistente con il threadId specificato e runCreateRequest e ottiene in modo asincrono la risposta dell'assistente
type: docs
weight: 410
url: /it/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## Metodo IOpenAIClient.RunAndGetAssistantResponseAsync

Esegue l'assistente con il threadId specificato e runCreateRequest, e ottiene in modo asincrono la risposta dell'assistente.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread. |
| runCreateRequest | RunCreateRequest | La richiesta di creazione dell'esecuzione. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona con la stringa di risposta dell'assistente.

### Vedi Anche

* classe [RunCreateRequest](../../runcreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)