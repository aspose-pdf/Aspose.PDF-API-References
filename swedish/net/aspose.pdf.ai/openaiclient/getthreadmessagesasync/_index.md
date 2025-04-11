---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar en lista med meddelanden för en specifik tråd asynkront
type: docs
weight: 320
url: /sv/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync metod

Hämtar en lista med meddelanden för en specifik tråd asynkront.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden att hämta meddelanden från. |
| queryParameters | ThreadMessageListQueryParameters | Valfria frågeparametrar för att filtrera listan med meddelanden. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftens resultat innehåller en lista med trådmeddelanden.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |

### Se Även

* klass [ThreadMessageListResponse](../../threadmessagelistresponse/)
* klass [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)