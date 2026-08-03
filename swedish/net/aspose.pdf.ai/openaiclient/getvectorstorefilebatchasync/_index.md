---
title: "OpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Hämtar detaljer för en specifik vector store‑filbatch asynkront"
type: docs
weight: 360
url: /sv/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync method

Hämtar detaljer för en specifik vektorlagerfilbatch asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vector store som innehåller filbatchen. |
| fileBatchId | String | ID för filbatchen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task‑resultatet innehåller detaljerna för filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när vector store‑filbatch‑Id är null eller tomt. |

### Se även

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


