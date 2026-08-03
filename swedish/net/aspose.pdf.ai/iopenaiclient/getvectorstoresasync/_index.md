---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar en lista över vektorlager asynkront"
type: docs
weight: 350
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync method

Hämtar en lista med vektorlager asynkront.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Valfria frågeparametrar för att filtrera listan över vektorlager. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över vektorlager.

### Se även

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


