---
title: "OpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Väntar på att ett specifikt vector store ska slutföras asynkront"
type: docs
weight: 510
url: /sv/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## OpenAIClient.WaitForVectorStoreToCompleteAsync method

Väntar asynkront på att ett specifikt vektorlager ska slutföras.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vector store som ska övervakas tills den är klar. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task‑resultatet innehåller den slutgiltiga statusen för vector store.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


