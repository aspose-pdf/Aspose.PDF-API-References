---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo archivio vettoriale in modo asincrono
type: docs
weight: 100
url: /it/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## Metodo IOpenAIClient.CreateVectorStoreAsync

Crea un nuovo archivio vettoriale in modo asincrono.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | L'oggetto di richiesta contenente i dettagli per la creazione dell'archivio vettoriale. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione dell'archivio vettoriale.

### Vedi anche

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)