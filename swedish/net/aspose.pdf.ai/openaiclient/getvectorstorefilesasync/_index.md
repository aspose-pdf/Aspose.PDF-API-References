---
title: "OpenAIClient.GetVectorStoreFilesAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Hämtar en lista med filer i ett specifikt vector store asynkront"
type: docs
weight: 380
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync method

Hämtar en lista med filer inom ett specifikt vektorlager asynkront.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vector store som innehåller filerna. |
| queryParameters | VectorStoreFileListQueryParameters | Valfria frågeparametrar för att filtrera listan med filer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task‑resultatet innehåller en lista med filer i vector store.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


