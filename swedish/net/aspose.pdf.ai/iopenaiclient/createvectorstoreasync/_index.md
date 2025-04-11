---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en ny vektorbutik asynkront
type: docs
weight: 100
url: /sv/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync metod

Skapar en ny vektorbutik asynkront.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa vektorbutiken. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från skapandet av vektorbutiken.

### Se Även

* klass [VectorStoreResponse](../../vectorstoreresponse/)
* klass [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)