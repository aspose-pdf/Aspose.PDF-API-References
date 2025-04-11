---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot-gränssnitt. Representerar en chattkopilot för att interagera med dokument via AI-modeller
type: docs
weight: 470
url: /sv/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot-gränssnitt

Representerar en chattkopilot för att interagera med dokument via AI-modeller.

```csharp
public interface IChatCopilot : IAICopilot
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Asynkront tar bort kontexten. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Asynkront hämtar ett svar för den angivna listan av meddelanden. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Asynkront hämtar ett svar för det angivna meddelandet. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Asynkront sparar kontexten till en JSON-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Asynkront sparar svaren för den angivna listan av meddelanden till en PDF-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Asynkront sparar svaret för det angivna meddelandet till en PDF-fil. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Asynkront sparar svaren för den angivna listan av meddelanden till en fil med angivet format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Asynkront sparar svaret för det angivna meddelandet till en fil med angivet format. |

### Se Även

* gränssnitt [IAICopilot](../iaicopilot/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)