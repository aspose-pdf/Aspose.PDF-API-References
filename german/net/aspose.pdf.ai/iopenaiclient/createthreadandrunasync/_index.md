---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Erstellt einen Thread und führt ihn asynchron aus
type: docs
weight: 60
url: /de/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync-Methode

Erstellt einen Thread und führt ihn asynchron aus.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Die Anforderungsdetails zum Erstellen des Threads und der Ausführung. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Erstellung des Threads und der Ausführung.

### Siehe auch

* Klasse [RunResponse](../../runresponse/)
* Klasse [RunThreadCreateRequest](../../runthreadcreaterequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)