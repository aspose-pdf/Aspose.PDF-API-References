---
title: "IOpenAIClient.ModifyThreadAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient-metod. Ändrar en befintlig tråd asynkront"
type: docs
weight: 380
url: /sv/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## IOpenAIClient.ModifyThreadAsync method

Modifierar en befintlig tråd asynkront.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden som ska modifieras. |
| threadModifyRequest | ThreadModifyRequest | Begäranobjektet som innehåller modifieringsdetaljer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En Task som representerar den asynkrona operationen. Task-resultatet innehåller svaret från trådförändringen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när tråd-Id är null eller tomt. |

### Se även

* class [ThreadResponse](../../threadresponse/)
* class [ThreadModifyRequest](../../threadmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


