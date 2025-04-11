---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar en lista över vektorbutiker asynkront
type: docs
weight: 350
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync metod

Hämtar en lista över vektorbutiker asynkront.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Valfria frågeparametrar för att filtrera listan över vektorbutiker. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över vektorbutiker.

### Se Även

* klass [VectorStoreListResponse](../../vectorstorelistresponse/)
* klass [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)