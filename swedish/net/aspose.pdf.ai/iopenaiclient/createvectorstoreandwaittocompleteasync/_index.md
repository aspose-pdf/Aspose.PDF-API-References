---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en ny vektorbutik och väntar på att den ska slutföras asynkront
type: docs
weight: 90
url: /sv/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync metod

Skapar en ny vektorbutik och väntar på att den ska slutföras asynkront.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa vektorbutiken. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från skapandet av vektorbutiken efter slutförande.

### Se Även

* klass [VectorStoreResponse](../../vectorstoreresponse/)
* klass [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)