---
title: "OpenAIClient.DeleteThreadAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Raderar en befintlig tråd asynkront"
type: docs
weight: 150
url: /sv/net/aspose.pdf.ai/openaiclient/deletethreadasync/
---
## OpenAIClient.DeleteThreadAsync method

Raderar en befintlig tråd asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden att radera. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för raderingsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


