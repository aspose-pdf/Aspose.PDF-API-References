---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un thread e un run al suo interno in modo asincrono
type: docs
weight: 60
url: /it/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## Metodo IOpenAIClient.CreateThreadAndRunAsync

Crea un thread e un run al suo interno in modo asincrono.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | I dettagli della richiesta per creare il thread e il run. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del thread e del run.

### Vedi Anche

* classe [RunResponse](../../runresponse/)
* classe [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)