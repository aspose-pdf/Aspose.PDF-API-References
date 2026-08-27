---
title: "OpenAIClient.ModifyAssistantAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Modifierar en befintlig assistent asynkront"
type: docs
weight: 400
url: /sv/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## OpenAIClient.ModifyAssistantAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


