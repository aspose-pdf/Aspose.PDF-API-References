---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Hämtar detaljer om en specifik assistent asynkront
type: docs
weight: 190
url: /sv/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## IOpenAIClient.GetAssistantAsync metod

Hämtar detaljer om en specifik assistent asynkront.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assistantId | Sträng | ID:t för den assistent som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna om assistenten.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när assistent-ID:t är null eller tomt. |

### Se Även

* klass [AssistantResponse](../../assistantresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)