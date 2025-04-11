---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar en lista över steg för en specifik körning inom en tråd asynkront
type: docs
weight: 260
url: /sv/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync metod

Hämtar en lista över steg för en specifik körning inom en tråd asynkront.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden som innehåller körningen. |
| runId | Sträng | ID:t för körningen att hämta steg från. |
| queryParameters | RunStepListQueryParameters | Valfria frågeparametrar för att filtrera listan över körsteg. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller listan över körsteg.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när tråd-ID:t är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när kör-ID:t är null eller tomt. |

### Se Även

* klass [RunStepListResponse](../../runsteplistresponse/)
* klass [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)