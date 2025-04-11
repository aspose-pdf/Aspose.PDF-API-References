---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar detaljer om en specifik vektorlagerfilbatch asynkront
type: docs
weight: 320
url: /sv/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## IOpenAIClient.GetVectorStoreFileBatchAsync metod

Hämtar detaljer om en specifik vektorlagerfilbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorlageret som innehåller filbatchen. |
| fileBatchId | Sträng | ID:t för filbatchen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljer om filbatchen.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlager-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorlagerfilbatch-ID:t är null eller tomt. |

### Se Även

* klass [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)