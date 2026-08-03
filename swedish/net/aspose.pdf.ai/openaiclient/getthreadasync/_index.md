---
title: "OpenAIClient.GetThreadAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient metod. Hämtar detaljer för en specifik tråd asynkront"
type: docs
weight: 310
url: /sv/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## OpenAIClient.GetThreadAsync method

Hämtar detaljer för en specifik tråd asynkront.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID‑t för tråden att hämta. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

Ett uppdrag som representerar den asynkrona operationen. Uppgiftsresultatet innehåller trådens detaljer.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [ThreadResponse](../../threadresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


