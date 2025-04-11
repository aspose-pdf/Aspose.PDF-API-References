---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAISummaryCopilotOptions-Klasse. Stellt die Optionen zur Konfiguration des OpenAICopilot dar
type: docs
weight: 930
url: /de/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions-Klasse

Stellt die Optionen zur Konfiguration des OpenAICopilot dar.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Ruft den Namen des Assistenten ab oder legt ihn fest. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ruft die Sammlung von Dokumenten ab oder legt sie fest, die verarbeitet werden sollen. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab oder legt sie fest, die im Verlauf des Laufs verwendet werden dürfen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Eingabe-Token ab oder legt sie fest, die im Verlauf des Laufs verwendet werden dürfen. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Ruft das Modell ab oder legt es fest, das für den Assistenten verwendet werden soll. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Ruft die Eingabeaufforderung ab oder legt sie fest, um das Modell anzuweisen, eine Dokumentenzusammenfassung bereitzustellen. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ruft den Dateipfad für die Textdatei ab oder legt ihn fest, die die Systemanweisungen des Assistenten enthält. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ruft die Sampling-Temperatur ab oder legt sie fest, die für das Modell verwendet werden soll. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ruft den Top-p-Wert für die Kernstichprobe ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | Erstellt eine neue Instanz von `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | Erstellt eine Instanz von `OpenAISummaryCopilotOptions` und konfiguriert sie mit dem bereitgestellten Delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Ruft die aktuellen `OpenAISummaryCopilotOptions` ab. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Legt den Assistentennamen für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Fügt ein PDF-Dokument zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Fügt einen Dokumentpfad zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Fügt ein Textdokument zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Legt die Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Fügt mehrere PDF-Dokumente zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Fügt mehrere Dokumentpfade zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Fügt mehrere Textdokumente zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Legt die Anweisungen für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Legt die maximalen Abschluss-Token für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Legt die maximalen Eingabe-Token für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Legt das Modell für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Legt die Zusammenfassungsaufforderung für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Legt die Temperatur für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Legt den Top-P-Wert für die Zusammenfassungs-Copilot-Optionen fest. |

### Siehe auch

* Klasse [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* Schnittstelle [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* Namensraum [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)