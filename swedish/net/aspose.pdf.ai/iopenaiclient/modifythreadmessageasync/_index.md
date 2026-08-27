---
title: "IOpenAIClient.ModifyThreadMessageAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Ändrar ett befintligt meddelande i en tråd asynkront"
type: docs
weight: 390
url: /sv/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync method

Modifierar ett befintligt meddelande inom en tråd asynkront.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som innehåller meddelandet som ska modifieras. |
| threadMessageId | String | ID för meddelandet som ska modifieras. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Begärans detaljer för att modifiera meddelandet. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller svaret från meddelandeförändringen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när trådens meddelande‑Id är null eller tomt. |

### Se även

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


