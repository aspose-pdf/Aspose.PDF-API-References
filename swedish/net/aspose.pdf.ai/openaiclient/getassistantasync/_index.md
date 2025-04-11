---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar detaljer om en specifik assistent asynkront
type: docs
weight: 190
url: /sv/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync metod

Hämtar detaljer om en specifik assistent asynkront.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantId | Sträng | ID:t för assistenten som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna om assistenten.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när assistent-ID:t är null eller tomt. |

### Se Även

* klass [AssistantResponse](../../assistantresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)