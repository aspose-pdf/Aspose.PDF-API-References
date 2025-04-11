---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar en lista över filer inom en specifik vektorbutik asynkront
type: docs
weight: 370
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync metod

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

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens Id är null eller tom. |

### Se Även

* klass [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* klass [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)