---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Modifierar ett befintligt meddelande inom en tråd asynkront
type: docs
weight: 420
url: /sv/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync metod

Modifierar ett befintligt meddelande inom en tråd asynkront.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller meddelandet som ska modifieras. |
| threadMessageId | Sträng | ID:t för meddelandet som ska modifieras. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Begärningsdetaljer för att modifiera meddelandet. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från meddelandemodifieringen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när trådmeddelande-ID:t är null eller tomt. |

### Se Även

* klass [ThreadMessageResponse](../../threadmessageresponse/)
* klass [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)