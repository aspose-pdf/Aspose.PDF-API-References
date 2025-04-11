---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Modifierar en befintlig assistent asynkront
type: docs
weight: 360
url: /sv/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync metod

Modifierar en befintlig assistent asynkront.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantId | Sträng | ID:t för assistenten som ska modifieras. |
| assistantModifyRequest | AssistantModifyRequest | Begärningsobjektet som innehåller modifieringsdetaljer. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från assistentens modifiering.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när assistentens ID är null eller tomt. |

### Se Även

* klass [AssistantResponse](../../assistantresponse/)
* klass [AssistantModifyRequest](../../assistantmodifyrequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)