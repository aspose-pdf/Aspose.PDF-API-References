---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft Details eines bestimmten Assistenten asynchron ab
type: docs
weight: 190
url: /de/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## IOpenAIClient.GetAssistantAsync-Methode

Ruft Details eines bestimmten Assistenten asynchron ab.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| assistantId | String | Die ID des abzurufenden Assistenten. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Details des Assistenten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Assistenten-ID null oder leer ist. |

### Siehe auch

* Klasse [AssistantResponse](../../assistantresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)