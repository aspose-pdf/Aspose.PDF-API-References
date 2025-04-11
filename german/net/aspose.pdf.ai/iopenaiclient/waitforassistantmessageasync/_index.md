---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Wartet asynchron auf die erste Nachricht des Assistenten innerhalb eines Threads
type: docs
weight: 430
url: /de/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync-Methode

Wartet asynchron auf die erste Nachricht des Assistenten innerhalb eines Threads.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, um die erste Nachricht des Assistenten zu überwachen. |
| queryParameters | ThreadMessageListQueryParameters | Optionale Abfrageparameter zum Filtern der Nachrichtenliste. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die erste Nachricht des Assistenten im Thread.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageResponse](../../threadmessageresponse/)
* Klasse [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)