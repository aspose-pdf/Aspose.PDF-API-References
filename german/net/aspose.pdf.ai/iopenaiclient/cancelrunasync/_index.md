---
title: IOpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Kündigt einen bestehenden Lauf innerhalb eines Threads asynchron.
type: docs
weight: 10
url: /de/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync-Methode

Kündigt einen bestehenden Lauf innerhalb eines Threads asynchron.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der den zu kündigenden Lauf enthält. |
| runId | String | Die ID des zu kündigenden Laufs. |
| cancellationToken | Nullable`1 | Ein Token zur Kündigung der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Laufkündigung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Lauf-ID null oder leer ist. |

### Siehe auch

* Klasse [RunResponse](../../runresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)