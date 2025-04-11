---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Löscht eine Nachricht innerhalb eines Threads asynchron
type: docs
weight: 160
url: /de/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync-Methode

Löscht eine Nachricht innerhalb eines Threads asynchron.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der die zu löschende Nachricht enthält. |
| threadMessageId | String | Die ID der zu löschenden Nachricht. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält den Status der Löschoperation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-Nachrichten-ID null oder leer ist. |

### Siehe auch

* Klasse [DeleteStatusResponse](../../deletestatusresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)