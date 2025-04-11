---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Kör assistenten med det angivna threadId och runCreateRequest och får asynkront assistentens svar
type: docs
weight: 410
url: /sv/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync metod

Kör assistenten med det angivna threadId och runCreateRequest, och får asynkront assistentens svar.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | Sträng | ID för tråden. |
| runCreateRequest | RunCreateRequest | Begäran om att skapa en körning. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen med assistentens svarsträng.

### Se Även

* klass [RunCreateRequest](../../runcreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)