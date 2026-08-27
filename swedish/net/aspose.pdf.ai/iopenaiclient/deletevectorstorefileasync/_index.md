---
title: "IOpenAIClient.DeleteVectorStoreFileAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Raderar en fil inom en vector store asynkront"
type: docs
weight: 180
url: /sv/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## IOpenAIClient.DeleteVectorStoreFileAsync method

Raderar en fil i ett vektorlager asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager som innehåller filen som ska raderas. |
| fileId | String | ID för filen som ska raderas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för raderingsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när fil‑ID är null eller tomt. |

### Se även

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


