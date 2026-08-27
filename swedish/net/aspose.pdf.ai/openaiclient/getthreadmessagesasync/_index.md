---
title: "OpenAIClient.GetThreadMessagesAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Hämtar en lista med meddelanden för en specifik tråd asynkront"
type: docs
weight: 330
url: /sv/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync method

Hämtar en lista med meddelanden för en specifik tråd asynkront.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden att hämta meddelanden från. |
| queryParameters | ThreadMessageListQueryParameters | Valfria frågeparametrar för att filtrera listan med meddelanden. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller en lista med trådmeldanden.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


