---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar en lista över filer inom en specifik vektorlagerfilbatch asynkront
type: docs
weight: 360
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## OpenAIClient.GetVectorStoreFileBatchFilesAsync metod

Hämtar en lista över filer inom en specifik vektorlagerfilbatch asynkront.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorlager som innehåller filbatchen. |
| fileBatchId | Sträng | ID:t för filbatchen att hämta filer från. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Valfria frågeparametrar för att filtrera listan över filer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över filer inom filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlager-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlagerfilbatch-ID:t är null eller tomt. |

### Se Även

* klass [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* klass [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)