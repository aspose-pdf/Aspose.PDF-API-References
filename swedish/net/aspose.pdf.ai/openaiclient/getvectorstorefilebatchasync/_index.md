---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar detaljer om en specifik vektorlagerfilbatch asynkront
type: docs
weight: 350
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync metod

Hämtar detaljer om en specifik vektorlagerfilbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorlager som innehåller filbatchen. |
| fileBatchId | Sträng | ID:t för filbatchen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna om filbatchen.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlager-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlagerfilbatch-ID:t är null eller tomt. |

### Se Även

* klass [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)