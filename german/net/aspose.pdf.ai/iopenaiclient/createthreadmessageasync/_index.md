---
title: IOpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Erstellt eine neue Nachricht innerhalb eines Threads asynchron
type: docs
weight: 80
url: /de/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync-Methode

Erstellt eine neue Nachricht innerhalb eines Threads asynchron.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, in dem die Nachricht erstellt wird. |
| threadMessageRequest | ThreadMessageCreateRequest | Die Anforderungsdetails zum Erstellen der Nachricht. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Nachrichtencreation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageResponse](../../threadmessageresponse/)
* Klasse [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)