---
title: "OpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Väntar asynkront på det första meddelandet från assistenten i en tråd"
type: docs
weight: 470
url: /sv/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync method

Väntar asynkront på det första meddelandet från assistenten inom en tråd.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden att övervaka för det första assistentmeddelandet. |
| queryParameters | ThreadMessageListQueryParameters | Valfria frågeparametrar för att filtrera listan med meddelanden. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftens resultat innehåller det första assistentmeddelandet i tråden.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


