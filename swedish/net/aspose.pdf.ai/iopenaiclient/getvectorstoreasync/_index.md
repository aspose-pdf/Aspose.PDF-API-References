---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar detaljer om en specifik vektorbutik asynkront
type: docs
weight: 300
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync metod

Hämtar detaljer om en specifik vektorbutik asynkront.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna om vektorbutiken.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens Id är null eller tom. |

### Se Även

* klass [VectorStoreResponse](../../vectorstoreresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)