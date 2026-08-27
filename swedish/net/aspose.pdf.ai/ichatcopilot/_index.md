---
title: "Gränssnitt IChatCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.IChatCopilot-gränssnitt. Representerar en chattkopilot för att interagera med dokument via AI-modeller."
type: docs
weight: 490
url: /sv/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

Representerar en chattcopilot för att interagera med dokument via AI-modeller.

```csharp
public interface IChatCopilot : IAICopilot
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Tar asynkront bort kontexten. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Hämtar asynkront ett svar för den angivna listan med meddelanden. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Hämtar asynkront ett svar för det angivna meddelandet. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Sparar asynkront kontexten till en JSON-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Sparar asynkront svaren för den angivna listan med meddelanden till en PDF-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Sparar asynkront svaret för det angivna meddelandet till en PDF-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Sparar asynkront svaren för den angivna listan med meddelanden till en fil med angivet format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Sparar asynkront svaret för det angivna meddelandet till en fil med angivet format. |

### Se även

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


