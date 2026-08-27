---
title: "OpenAIClient.DeleteVectorStoreAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Tar bort ett vektorlager asynkront."
type: docs
weight: 170
url: /sv/net/aspose.pdf.ai/openaiclient/deletevectorstoreasync/
---
## OpenAIClient.DeleteVectorStoreAsync method

Raderar ett vektorlager asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager att ta bort. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för raderingsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


