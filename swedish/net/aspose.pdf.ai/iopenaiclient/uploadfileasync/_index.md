---
title: "IOpenAIClient.UploadFileAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient-metod. Laddar upp en fil asynkront till OpenAI-servern"
type: docs
weight: 420
url: /sv/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

Laddar upp en fil asynkront till OpenAI-servern.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| `purpose` | String | Syftet med filuppladdningen, beskriver vanligtvis hur filen kommer att användas. |
| `fileName` | String | Namnet på filen som ska laddas upp. |
| `fileBytes` | Byte[] | Byte‑arrayen som innehåller filens data. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller svaret från filuppladdningen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när filens syfte är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när filnamnet är null eller tomt. |

### Se även

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


