---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Tar bort ett meddelande inom en tråd asynkront
type: docs
weight: 160
url: /sv/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync metod

Tar bort ett meddelande inom en tråd asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller meddelandet som ska tas bort. |
| threadMessageId | Sträng | ID:t för meddelandet som ska tas bort. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för borttagningsoperationen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när trådmeddelande-ID:t är null eller tomt. |

### Se Även

* klass [DeleteStatusResponse](../../deletestatusresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)