---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Modifiziert eine vorhandene Nachricht innerhalb eines Threads asynchron
type: docs
weight: 390
url: /de/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync-Methode

Modifiziert eine vorhandene Nachricht innerhalb eines Threads asynchron.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der die zu modifizierende Nachricht enthält. |
| threadMessageId | String | Die ID der zu modifizierenden Nachricht. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Die Anforderungsdetails zur Modifizierung der Nachricht. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort auf die Nachrichtenmodifikation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-Nachrichten-ID null oder leer ist. |

### Siehe auch

* Klasse [ThreadMessageResponse](../../threadmessageresponse/)
* Klasse [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)