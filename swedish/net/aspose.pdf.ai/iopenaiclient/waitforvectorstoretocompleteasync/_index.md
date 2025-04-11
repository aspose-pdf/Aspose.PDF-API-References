---
title: IOpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Väntar på att en specifik vektorbutik ska slutföras asynkront
type: docs
weight: 470
url: /sv/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreToCompleteAsync metod

Väntar på att en specifik vektorbutik ska slutföras asynkront.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som ska övervakas tills den är slutförd. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller det slutgiltiga tillståndet för vektorbutiken.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens ID är null eller tomt. |

### Se Även

* klass [VectorStoreResponse](../../vectorstoreresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)