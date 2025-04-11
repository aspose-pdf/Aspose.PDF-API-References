---
title: OpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. La creazione di un thread e di un run all'interno di esso in modo asincrono.
type: docs
weight: 60
url: /it/net/aspose.pdf.ai/openaiclient/createthreadandrunasync/
---
## OpenAIClient.CreateThreadAndRunAsync metodo

Crea un thread e un run al suo interno in modo asincrono.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | I dettagli della richiesta per creare il thread e il run. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Return Value

Un task che rappresenta l'operazione asincrona. Il risultato del task contiene la risposta dalla creazione del thread e del run.

### See Also

* classe [RunResponse](../../runresponse/)
* classe [RunThreadCreateRequest](../../runthreadcreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)