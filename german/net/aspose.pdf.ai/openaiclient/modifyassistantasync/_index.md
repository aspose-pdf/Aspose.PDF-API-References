---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Modifiziert einen bestehenden Assistenten asynchron
type: docs
weight: 390
url: /de/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## OpenAIClient.ModifyAssistantAsync-Methode

Modifiziert einen bestehenden Assistenten asynchron.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| assistantId | String | Die ID des zu modifizierenden Assistenten. |
| assistantModifyRequest | AssistantModifyRequest | Das Anforderungsobjekt, das die Modifikationsdetails enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Assistentenmodifikation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Assistenten-ID null oder leer ist. |

### Siehe auch

* Klasse [AssistantResponse](../../assistantresponse/)
* Klasse [AssistantModifyRequest](../../assistantmodifyrequest/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)