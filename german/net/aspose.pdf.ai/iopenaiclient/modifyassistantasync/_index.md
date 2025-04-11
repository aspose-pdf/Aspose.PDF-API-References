---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Modifiziert einen vorhandenen Assistenten asynchron
type: docs
weight: 360
url: /de/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync-Methode

Modifiziert einen vorhandenen Assistenten asynchron.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| assistantId | String | Die ID des zu modifizierenden Assistenten. |
| assistantModifyRequest | AssistantModifyRequest | Das Anfrageobjekt, das die Änderungsdetails enthält. |
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
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)