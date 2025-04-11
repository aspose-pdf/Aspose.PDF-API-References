---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Väntar på att ett specifikt trådmeddelande ska slutföras asynkront
type: docs
weight: 450
url: /sv/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync metod

Väntar på att ett specifikt trådmeddelande ska slutföras asynkront.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller meddelandet. |
| threadMessageId | Sträng | ID:t för meddelandet som ska övervakas tills det är slutfört. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller det slutgiltiga status för meddelandet.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när trådmeddelande-ID:t är null eller tomt. |

### Se Även

* klass [ThreadMessageResponse](../../threadmessageresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)