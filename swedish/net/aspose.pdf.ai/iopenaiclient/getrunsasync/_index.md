---
title: "IOpenAIClient.GetRunsAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Hämtar en lista över körningar för en specificerad tråd asynkront"
type: docs
weight: 240
url: /sv/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## IOpenAIClient.GetRunsAsync method

Hämtar en lista över körningar för en specificerad tråd asynkront.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden att hämta körningar från. |
| queryParameters | RunListQueryParameters | Valfria frågeparametrar för att filtrera listan med körningar. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftens resultat innehåller en lista med körningar.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


