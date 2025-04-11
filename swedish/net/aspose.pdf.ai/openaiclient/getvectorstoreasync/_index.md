---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar detaljer om en specifik vektorbutik asynkront
type: docs
weight: 330
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync metod

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
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens ID är null eller tomt. |

### Se Även

* klass [VectorStoreResponse](../../vectorstoreresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)