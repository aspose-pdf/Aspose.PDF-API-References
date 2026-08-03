---
title: "OpenAIClient.DeleteFileAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Raderar en specifik fil asynkront"
type: docs
weight: 140
url: /sv/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## OpenAIClient.DeleteFileAsync method

Raderar en specifik fil asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileId | String | ID för filen som ska raderas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för raderingsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när fil‑ID är null eller tomt. |

### Se även

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


