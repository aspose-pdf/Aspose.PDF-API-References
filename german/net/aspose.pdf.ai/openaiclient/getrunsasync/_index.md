---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft eine Liste von Ausführungen für einen bestimmten Thread asynchron ab
type: docs
weight: 260
url: /de/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync-Methode

Ruft eine Liste von Ausführungen für einen bestimmten Thread asynchron ab.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads, von dem Ausführungen abgerufen werden sollen. |
| queryParameters | RunListQueryParameters | Optionale Abfrageparameter zum Filtern der Liste von Ausführungen. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Ausführungen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Thread-ID null oder leer ist. |

### Siehe auch

* Klasse [RunListResponse](../../runlistresponse/)
* Klasse [RunListQueryParameters](../../runlistqueryparameters/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)