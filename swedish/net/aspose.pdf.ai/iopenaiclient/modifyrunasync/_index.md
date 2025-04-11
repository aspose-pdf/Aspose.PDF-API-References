---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Modifierar en befintlig körning inom en tråd asynkront
type: docs
weight: 370
url: /sv/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## IOpenAIClient.ModifyRunAsync metod

Modifierar en befintlig körning inom en tråd asynkront.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller körningen. |
| runId | Sträng | ID:t för körningen som ska modifieras. |
| assistantModifyRequest | RunModifyRequest | Begärningsdetaljer för att modifiera körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från körningsmodifieringen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när körnings-ID:t är null eller tomt. |

### Se Även

* klass [RunResponse](../../runresponse/)
* klass [RunModifyRequest](../../runmodifyrequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)