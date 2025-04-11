---
title: OpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Erstellt asynchron eine neue Completion.
type: docs
weight: 40
url: /de/net/aspose.pdf.ai/openaiclient/createcompletionasync/
---
## OpenAIClient.CreateCompletionAsync Methode

Erstellt asynchron eine neue Completion.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parameter                | Typ                 | Beschreibung                                                                           |
| ------------------------ | ------------------- | -------------------------------------------------------------------------------------- |
| completionCreateRequest  | CompletionCreateRequest | Das Anforderungsobjekt, das Details zum Erstellen der Completion enthält.             |
| cancellationToken        | Nullable`1          | Ein Token zum Abbrechen des Vorgangs.                                                  |

### Rückgabewert

Ein Task, der die asynchrone Operation darstellt. Das Ergebnis des Tasks enthält die Antwort der Completion-Erstellung.

### Siehe auch

* Klasse [CompletionResponse](../../completionresponse/)
* Klasse [CompletionCreateRequest](../../completioncreaterequest/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)