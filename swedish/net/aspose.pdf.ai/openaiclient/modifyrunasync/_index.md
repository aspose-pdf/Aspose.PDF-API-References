---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Modifierar en befintlig körning i en tråd asynkront."
type: docs
weight: 410
url: /sv/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync method

Modifierar en befintlig körning inom en tråd asynkront.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som innehåller körningen. |
| runId | String | ID för körningen som ska modifieras. |
| assistantModifyRequest | RunModifyRequest | Begärans detaljer för att modifiera körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task‑resultatet innehåller svaret från körningsmodifieringen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när körnings‑ID är null eller tomt. |

### Se även

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


