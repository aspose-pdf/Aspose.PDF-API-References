---
title: "IOpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient-metod. Hämtar en lista med filer asynkront baserat på det angivna syftet"
type: docs
weight: 220
url: /sv/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync method

Hämtar en lista över filer asynkront baserat på det angivna syftet.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| `purpose` | String | Valfritt. Syftet med filerna som ska hämtas. Om null hämtas filer för alla syften. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller en lista med filer.

### Se även

* class [FileListResponse](../../filelistresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


