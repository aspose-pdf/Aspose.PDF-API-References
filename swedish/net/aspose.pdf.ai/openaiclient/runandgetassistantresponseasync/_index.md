---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Kör assistenten med det angivna threadId och runCreateRequest och får asynkront assistentens svar
type: docs
weight: 440
url: /sv/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync metod

Kör assistenten med det angivna threadId och runCreateRequest, och får asynkront assistentens svar.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID:t för tråden. |
| runCreateRequest | RunCreateRequest | Begäran om att skapa körning. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen med assistentens svarsträng.

### Se Även

* klass [RunCreateRequest](../../runcreaterequest/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)