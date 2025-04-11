---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Wartet darauf, dass eine bestimmte Thread-Nachricht asynchron abgeschlossen wird
type: docs
weight: 450
url: /de/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync-Methode

Wartet darauf, dass eine bestimmte Thread-Nachricht asynchron abgeschlossen wird.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der die Nachricht enthält. |
| threadMessageId | String | Die ID der Nachricht, die bis zum Abschluss überwacht werden soll. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält den endgültigen Status der Nachricht.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-Nachricht-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageResponse](../../threadmessageresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)