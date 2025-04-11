---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft eine Liste von Nachrichten für einen bestimmten Thread asynchron ab
type: docs
weight: 290
url: /de/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## IOpenAIClient.GetThreadMessagesAsync-Methode

Ruft eine Liste von Nachrichten für einen bestimmten Thread asynchron ab.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, aus dem Nachrichten abgerufen werden sollen. |
| queryParameters | ThreadMessageListQueryParameters | Optionale Abfrageparameter zum Filtern der Liste von Nachrichten. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Thread-Nachrichten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageListResponse](../../threadmessagelistresponse/)
* Klasse [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)