---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar en lista över filer inom en specifik vektorbutik asynkront
type: docs
weight: 340
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## IOpenAIClient.GetVectorStoreFilesAsync metod

Hämtar en lista över filer inom en specifik vektorbutik asynkront.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som innehåller filerna. |
| queryParameters | VectorStoreFileListQueryParameters | Valfria frågeparametrar för att filtrera listan över filer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över filer inom vektorbutiken.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens ID är null eller tomt. |

### Se Även

* klass [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* klass [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)