---
title: "OpenAIClient.GetRunStepsAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Hämtar en lista med steg för ett specifikt run i en tråd asynkront"
type: docs
weight: 290
url: /sv/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## OpenAIClient.GetRunStepsAsync method

Hämtar en lista med steg för en specifik körning inom en tråd asynkront.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som innehåller körningen. |
| runId | String | ID för run som steg ska hämtas från. |
| queryParameters | RunStepListQueryParameters | Valfria frågeparametrar för att filtrera listan över körsteg. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller listan över körsteg.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när körnings‑ID är null eller tomt. |

### Se även

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


