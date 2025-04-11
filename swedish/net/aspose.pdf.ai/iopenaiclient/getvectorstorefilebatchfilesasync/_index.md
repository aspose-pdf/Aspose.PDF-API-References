---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar en lista över filer inom en specifik vektorbutik filbatch asynkront
type: docs
weight: 330
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync metod

Hämtar en lista över filer inom en specifik vektorbutik filbatch asynkront.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som innehåller filbatchen. |
| fileBatchId | Sträng | ID:t för filbatchen att hämta filer från. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Valfria frågeparametrar för att filtrera listan över filer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över filer inom filbatchen.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens filbatch Id är null eller tomt. |

### Se Även

* klass [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* klass [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)