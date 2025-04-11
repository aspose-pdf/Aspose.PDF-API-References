---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar detaljer om ett specifikt steg inom en körning asynkront
type: docs
weight: 250
url: /sv/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync metod

Hämtar detaljer om ett specifikt steg inom en körning asynkront.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID för tråden som innehåller körningen. |
| runId | Sträng | ID för körningen som innehåller steget. |
| runStepId | Sträng | ID för körsteget som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljer om körsteget.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när kör-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när körstegs-ID är null eller tomt. |

### Se Även

* klass [RunStepResponse](../../runstepresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)