---
title: "IOpenAIClient.CreateRunAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Skapar en körning i en specificerad tråd asynkront"
type: docs
weight: 50
url: /sv/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync method

Skapar en körning inom en specificerad tråd asynkront.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden där körningen kommer att skapas. |
| runCreateRequest | RunCreateRequest | Begärans detaljer för att skapa körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller svaret från körningsskapandet.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


