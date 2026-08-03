---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Skapar ett nytt meddelande i en tråd asynkront"
type: docs
weight: 80
url: /sv/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

Skapar ett nytt meddelande i en tråd asynkront.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden där meddelandet kommer att skapas. |
| threadMessageRequest | ThreadMessageCreateRequest | Begärans detaljer för att skapa meddelandet. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task‑resultatet innehåller svaret från meddelandets skapande.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


