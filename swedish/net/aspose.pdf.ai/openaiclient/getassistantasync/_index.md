---
title: "OpenAIClient.GetAssistantAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Hämtar detaljer för en specifik assistent asynkront"
type: docs
weight: 190
url: /sv/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync method

Hämtar detaljer för en specifik assistent asynkront.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantId | String | ID för assistenten som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna för assistenten.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när assistent-Id är null eller tomt. |

### Se även

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


