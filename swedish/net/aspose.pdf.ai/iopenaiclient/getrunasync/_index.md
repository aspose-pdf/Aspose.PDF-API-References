---
title: "IOpenAIClient.GetRunAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar detaljer för en specifik körning i en tråd asynkront"
type: docs
weight: 230
url: /sv/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync method

Hämtar detaljer för en specifik körning i en tråd asynkront.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som innehåller körningen. |
| runId | String | ID:t för körningen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna för körningen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när körnings‑ID är null eller tomt. |

### Se även

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


