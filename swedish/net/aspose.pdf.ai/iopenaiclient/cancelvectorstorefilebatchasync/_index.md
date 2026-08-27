---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Avbryter en specifik vector store file batch asynkront"
type: docs
weight: 20
url: /sv/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

Avbryter en specifik vektorlagringsfilbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager som innehåller filbatchen som ska avbrytas. |
| fileBatchId | String | ID för filbatchen som ska avbrytas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från avbrytandet av filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när vector store‑filbatch‑Id är null eller tomt. |

### Se även

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


