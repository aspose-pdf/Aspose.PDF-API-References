---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar en lista över körningar för en angiven tråd asynkront
type: docs
weight: 260
url: /sv/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync metod

Hämtar en lista över körningar för en angiven tråd asynkront.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID för tråden att hämta körningar från. |
| queryParameters | RunListQueryParameters | Valfria frågeparametrar för att filtrera listan över körningar. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista över körningar.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |

### Se Även

* klass [RunListResponse](../../runlistresponse/)
* klass [RunListQueryParameters](../../runlistqueryparameters/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)