---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en ny assistent asynkront
type: docs
weight: 30
url: /sv/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## IOpenAIClient.CreateAssistantAsync metod

Skapar en ny assistent asynkront.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa assistenten. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från assistentskapandet.

### Se Även

* klass [AssistantResponse](../../assistantresponse/)
* klass [AssistantCreateRequest](../../assistantcreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)