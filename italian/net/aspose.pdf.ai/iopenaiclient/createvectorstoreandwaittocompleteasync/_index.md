---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo archivio vettoriale e attende che venga completato in modo asincrono
type: docs
weight: 90
url: /it/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## Metodo IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

Crea un nuovo archivio vettoriale e attende che venga completato in modo asincrono.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | L'oggetto di richiesta contenente i dettagli per la creazione dell'archivio vettoriale. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione dell'archivio vettoriale dopo il completamento.

### Vedi anche

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)