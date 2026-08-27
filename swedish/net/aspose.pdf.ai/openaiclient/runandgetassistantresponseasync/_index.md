---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient-metod. Kör assistenten med angivet threadId och runCreateRequest och hämtar assistentens svar asynkront"
type: docs
weight: 450
url: /sv/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

Kör assistenten med det angivna threadId och runCreateRequest, och hämtar asynkront assistentens svar.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadId | String | ID för tråden. |
| runCreateRequest | RunCreateRequest | Begäran om att skapa körning. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen med assistentens svarsträng.

### Se även

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


