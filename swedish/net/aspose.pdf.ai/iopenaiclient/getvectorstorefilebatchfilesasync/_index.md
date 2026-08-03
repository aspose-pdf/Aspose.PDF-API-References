---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar en lista med filer inom en specifik vector store file batch asynkront"
type: docs
weight: 330
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

Hämtar en lista med filer inom en specifik vektorlagerfilbatch asynkront.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vector store som innehåller filbatchen. |
| fileBatchId | String | ID‑t för filbatchen att hämta filer från. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Valfria frågeparametrar för att filtrera listan med filer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

Ett uppdrag som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista med filer inom filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när vector store‑filbatch‑Id är null eller tomt. |

### Se även

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


