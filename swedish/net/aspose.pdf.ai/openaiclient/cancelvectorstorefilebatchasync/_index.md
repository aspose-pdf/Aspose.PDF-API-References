---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Avbryter en specifik vektorbutik filbatch asynkront
type: docs
weight: 20
url: /sv/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## OpenAIClient.CancelVectorStoreFileBatchAsync metod

Avbryter en specifik vektorbutik filbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som innehåller filbatchen som ska avbrytas. |
| fileBatchId | Sträng | ID:t för filbatchen som ska avbrytas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från avbrytandet av filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens Id är null eller tom. |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens filbatch Id är null eller tom. |

### Se Även

* klass [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)