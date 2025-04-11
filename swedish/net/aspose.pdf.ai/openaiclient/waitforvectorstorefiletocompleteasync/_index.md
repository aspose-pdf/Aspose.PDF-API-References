---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Väntar på att en specifik vektorbutiksfil ska slutföras asynkront
type: docs
weight: 490
url: /sv/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## OpenAIClient.WaitForVectorStoreFileToCompleteAsync metod

Väntar på att en specifik vektorbutiksfil ska slutföras asynkront.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som innehåller filen. |
| fileId | Sträng | ID:t för filen som ska övervakas tills den är slutförd. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller det slutgiltiga status för filen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutiks-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när fil-ID:t är null eller tomt. |

### Se Även

* klass [VectorStoreFileResponse](../../vectorstorefileresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)