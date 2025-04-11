---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft eine Liste von Schritten für einen bestimmten Lauf innerhalb eines Threads asynchron ab
type: docs
weight: 260
url: /de/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync-Methode

Ruft eine Liste von Schritten für einen bestimmten Lauf innerhalb eines Threads asynchron ab.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, der den Lauf enthält. |
| runId | String | Die ID des Laufs, aus dem Schritte abgerufen werden sollen. |
| queryParameters | RunStepListQueryParameters | Optionale Abfrageparameter zur Filterung der Liste der Lauf Schritte. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Liste der Lauf Schritte.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Lauf-ID null oder leer ist. |

### Siehe auch

* Klasse [RunStepListResponse](../../runsteplistresponse/)
* Klasse [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)