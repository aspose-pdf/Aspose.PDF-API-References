---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten
type: docs
weight: 410
url: /de/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync-Methode

Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadId | String | Die ID des Threads. |
| runCreateRequest | RunCreateRequest | Die Anfrage zur Erstellung des Laufs. |
| cancellationToken | Nullable`1 | Das Abbruch-Token (optional). |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation mit der Antwort des Assistenten-Strings darstellt.

### Siehe auch

* Klasse [RunCreateRequest](../../runcreaterequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)