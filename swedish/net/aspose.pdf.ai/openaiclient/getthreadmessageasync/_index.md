---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar detaljer om ett specifikt meddelande inom en tråd asynkront
type: docs
weight: 310
url: /sv/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync metod

Hämtar detaljer om ett specifikt meddelande inom en tråd asynkront.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller meddelandet. |
| threadMessageId | Sträng | ID:t för meddelandet som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljer om trådmeddelandet.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när trådmeddelande-ID:t är null eller tomt. |

### Se Även

* klass [ThreadMessageResponse](../../threadmessageresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)