---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Skapar en körning inom en angiven tråd asynkront
type: docs
weight: 50
url: /sv/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync metod

Skapar en körning inom en angiven tråd asynkront.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden där körningen kommer att skapas. |
| runCreateRequest | RunCreateRequest | Begärningsdetaljer för att skapa körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från körningsskapandet.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |

### Se Även

* klass [RunResponse](../../runresponse/)
* klass [RunCreateRequest](../../runcreaterequest/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)