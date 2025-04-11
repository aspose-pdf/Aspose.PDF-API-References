---
title: IOpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft Details einer bestimmten Nachricht innerhalb eines Threads asynchron ab
type: docs
weight: 280
url: /de/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## IOpenAIClient.GetThreadMessageAsync-Methode

Ruft Details einer bestimmten Nachricht innerhalb eines Threads asynchron ab.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der die Nachricht enthält. |
| threadMessageId | String | Die ID der abzurufenden Nachricht. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Details der Thread-Nachricht.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-Nachrichten-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageResponse](../../threadmessageresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)