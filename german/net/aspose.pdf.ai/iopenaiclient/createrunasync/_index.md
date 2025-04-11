---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Erstellt einen Lauf innerhalb eines bestimmten Threads asynchron
type: docs
weight: 50
url: /de/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync-Methode

Erstellt einen Lauf innerhalb eines bestimmten Threads asynchron.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, in dem der Lauf erstellt wird. |
| runCreateRequest | RunCreateRequest | Die Anforderungsdetails zum Erstellen des Laufs. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Lauf-Erstellung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |

### Siehe auch

* Klasse [RunResponse](../../runresponse/)
* Klasse [RunCreateRequest](../../runcreaterequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)