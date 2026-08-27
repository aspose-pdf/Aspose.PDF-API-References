---
title: "IOpenAIClient.DeleteThreadMessageAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Tar bort ett meddelande i en tråd asynkront"
type: docs
weight: 160
url: /sv/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## IOpenAIClient.DeleteThreadMessageAsync method

Raderar ett meddelande i en tråd asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID:t för tråden som innehåller meddelandet som ska raderas. |
| threadMessageId | String | ID:t för meddelandet som ska raderas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för raderingsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när trådens meddelande‑Id är null eller tomt. |

### Se även

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


