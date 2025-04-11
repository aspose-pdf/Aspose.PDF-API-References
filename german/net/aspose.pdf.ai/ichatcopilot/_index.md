---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot-Schnittstelle. Stellt einen Chat-Copiloten für die Interaktion mit Dokumenten über KI-Modelle dar
type: docs
weight: 470
url: /de/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot-Schnittstelle

Stellt einen Chat-Copiloten für die Interaktion mit Dokumenten über KI-Modelle dar.

```csharp
public interface IChatCopilot : IAICopilot
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Löscht asynchron den Kontext. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Holt asynchron eine Antwort für die gegebene Liste von Nachrichten. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Holt asynchron eine Antwort für die gegebene Nachricht. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Speichert asynchron den Kontext in einer JSON-Datei. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Speichert asynchron die Antworten für die gegebene Liste von Nachrichten in einer PDF-Datei. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Speichert asynchron die Antwort für die gegebene Nachricht in einer PDF-Datei. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Speichert asynchron die Antworten für die gegebene Liste von Nachrichten in einer Datei mit dem angegebenen Format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Speichert asynchron die Antwort für die gegebene Nachricht in einer Datei mit dem angegebenen Format. |

### Siehe auch

* Schnittstelle [IAICopilot](../iaicopilot/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)