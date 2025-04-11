---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en körning inom en specificerad tråd asynkront
type: docs
weight: 50
url: /sv/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync metod

Skapar en körning inom en specificerad tråd asynkront.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID för tråden där körningen kommer att skapas. |
| runCreateRequest | RunCreateRequest | Begärningsdetaljer för att skapa körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från körningsskapandet.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID är null eller tomt. |

### Se Även

* klass [RunResponse](../../runresponse/)
* klass [RunCreateRequest](../../runcreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)