---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Modifiziert einen bestehenden Lauf innerhalb eines Threads asynchron
type: docs
weight: 370
url: /de/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## IOpenAIClient.ModifyRunAsync-Methode

Modifiziert einen bestehenden Lauf innerhalb eines Threads asynchron.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der den Lauf enthält. |
| runId | String | Die ID des zu modifizierenden Laufs. |
| assistantModifyRequest | RunModifyRequest | Die Anforderungsdetails zur Modifizierung des Laufs. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Laufmodifikation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Lauf-ID null oder leer ist. |

### Siehe auch

* Klasse [RunResponse](../../runresponse/)
* Klasse [RunModifyRequest](../../runmodifyrequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)