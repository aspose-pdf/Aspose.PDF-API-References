---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten
type: docs
weight: 440
url: /de/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync-Methode

Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads. |
| runCreateRequest | RunCreateRequest | Die Anfrage zur Erstellung des Laufs. |
| cancellationToken | Nullable`1 | Das Abbruchtoken (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation mit der Antwortzeichenfolge des Assistenten darstellt.

### Siehe auch

* Klasse [RunCreateRequest](../../runcreaterequest/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)