---
title: OpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar en lista över assistenter asynkront
type: docs
weight: 200
url: /sv/net/aspose.pdf.ai/openaiclient/getassistantsasync/
---
## OpenAIClient.GetAssistantsAsync metod

Hämtar en lista över assistenter asynkront.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Valfria frågeparametrar för att filtrera listan över assistenter. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller listan över assistenter.

### Se Även

* klass [AssistantListResponse](../../assistantlistresponse/)
* klass [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)