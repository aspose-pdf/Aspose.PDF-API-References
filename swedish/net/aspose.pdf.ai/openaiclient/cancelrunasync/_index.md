---
title: "OpenAIClient.CancelRunAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Avbryter en befintlig körning inom en tråd asynkront."
type: docs
weight: 10
url: /sv/net/aspose.pdf.ai/openaiclient/cancelrunasync/
---
## OpenAIClient.CancelRunAsync method

Avbryter en befintlig körning inom en tråd asynkront.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som innehåller körningen som ska avbrytas. |
| runId | String | ID för körningen som ska avbrytas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från avbrytandet av körningen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när körnings‑ID är null eller tomt. |

### Se även

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


