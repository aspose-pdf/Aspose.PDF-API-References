---
title: "IOpenAIClient.GetAssistantsAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar en lista över assistenter asynkront"
type: docs
weight: 200
url: /sv/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync method

Hämtar en lista över assistenter asynkront.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Valfria frågeparametrar för att filtrera listan med assistenter. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller listan med assistenter.

### Se även

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


