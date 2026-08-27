---
title: "IOpenAIClient.ModifyAssistantAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient-metod. Ändrar en befintlig assistent asynkront"
type: docs
weight: 360
url: /sv/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync method

Modifierar en befintlig assistent asynkront.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantId | String | ID för assistenten som ska modifieras. |
| assistantModifyRequest | AssistantModifyRequest | Begäranobjektet som innehåller modifieringsdetaljer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från assistentens modifiering.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när assistent-Id är null eller tomt. |

### Se även

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


