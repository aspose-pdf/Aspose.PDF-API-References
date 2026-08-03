---
title: "OpenAIClient.GetFileAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient metod. Hämtar detaljer för en specifik fil asynkront"
type: docs
weight: 220
url: /sv/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## OpenAIClient.GetFileAsync method

Hämtar detaljer för en specifik fil asynkront.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileId | String | ID för filen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller filens detaljer.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när fil‑ID är null eller tomt. |

### Se även

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


