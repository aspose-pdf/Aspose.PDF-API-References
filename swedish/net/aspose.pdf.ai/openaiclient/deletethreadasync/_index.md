---
title: OpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Tar bort en befintlig tråd asynkront
type: docs
weight: 150
url: /sv/net/aspose.pdf.ai/openaiclient/deletethreadasync/
---
## OpenAIClient.DeleteThreadAsync metod

Tar bort en befintlig tråd asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID för tråden som ska tas bort. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för borttagningsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID är null eller tomt. |

### Se Även

* klass [DeleteStatusResponse](../../deletestatusresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)