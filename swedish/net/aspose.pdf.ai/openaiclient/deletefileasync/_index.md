---
title: OpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Tar bort en specifik fil asynkront
type: docs
weight: 140
url: /sv/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## OpenAIClient.DeleteFileAsync metod

Tar bort en specifik fil asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileId | Sträng | ID:t för filen som ska tas bort. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för borttagningsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när fil-ID:t är null eller tomt. |

### Se Även

* klass [DeleteStatusResponse](../../deletestatusresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)