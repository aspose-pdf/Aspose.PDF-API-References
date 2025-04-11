---
title: OpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft Details eines bestimmten Laufs innerhalb eines Threads asynchron ab
type: docs
weight: 250
url: /de/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## OpenAIClient.GetRunAsync-Methode

Ruft Details eines bestimmten Laufs innerhalb eines Threads asynchron ab.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der den Lauf enthält. |
| runId | String | Die ID des Laufs, der abgerufen werden soll. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Details des Laufs.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Lauf-ID null oder leer ist. |

### Siehe auch

* Klasse [RunResponse](../../runresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)