---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Väntar på det första meddelandet från assistenten inom en tråd asynkront
type: docs
weight: 430
url: /sv/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync metod

Väntar på det första meddelandet från assistenten inom en tråd asynkront.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden att övervaka för det första assistentmeddelandet. |
| queryParameters | ThreadMessageListQueryParameters | Valfria frågeparametrar för att filtrera listan över meddelanden. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller det första assistentmeddelandet i tråden.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |

### Se Även

* klass [ThreadMessageResponse](../../threadmessageresponse/)
* klass [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)