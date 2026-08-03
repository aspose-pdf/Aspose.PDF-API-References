---
title: "IOpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar detaljer för en specifik vector store asynkront"
type: docs
weight: 300
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync method

Hämtar detaljer för ett specifikt vektorlager asynkront.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager att hämta. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna för vektorlager.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


