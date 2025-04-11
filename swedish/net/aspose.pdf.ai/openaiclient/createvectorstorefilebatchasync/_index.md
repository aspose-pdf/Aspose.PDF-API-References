---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Skapar en ny vektorbutik filbatch asynkront
type: docs
weight: 120
url: /sv/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync metod

Skapar en ny vektorbutik filbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken där filbatchen kommer att skapas. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa filbatchen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från filbatchskapandet.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens Id är null eller tom. |

### Se Även

* klass [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* klass [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)