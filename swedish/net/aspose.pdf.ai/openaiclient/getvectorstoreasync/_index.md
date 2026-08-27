---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient metod. Hämtar detaljer för en specifik vektorbutik asynkront"
type: docs
weight: 340
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


