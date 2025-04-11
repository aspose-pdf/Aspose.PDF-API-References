---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilotOptions-Klasse. Stellt die Optionen zur Konfiguration des OpenAICopilot dar
type: docs
weight: 750
url: /de/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions-Klasse

Stellt die Optionen zur Konfiguration des OpenAICopilot dar.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Ruft die Sammlung von zu verarbeitenden Dokumenten ab oder legt sie fest. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab oder legt sie fest, die im Verlauf des Laufs verwendet werden dürfen. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Ruft das Modell ab oder legt es fest, das für den Assistenten verwendet werden soll. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Ruft die Eingabeaufforderung ab oder legt sie fest, um das Modell anzuweisen, eine Dokumentenzusammenfassung bereitzustellen. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Ruft den Dateipfad für die Textdatei ab oder legt ihn fest, die die Systemanweisungen des Assistenten enthält. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Ruft die Sampling-Temperatur ab oder legt sie fest, die für das Modell verwendet werden soll. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Ruft den Top-p-Wert für die Kernstichprobe ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Erstellt eine neue Instanz von `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Erstellt eine Instanz von `LlamaSummaryCopilotOptions` und konfiguriert sie mit dem bereitgestellten Delegaten. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Ruft die aktuellen `LlamaSummaryCopilotOptions` ab. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Fügt ein PDF-Dokument zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Fügt einen Dokumentpfad zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Fügt ein Textdokument zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Legt die Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Fügt mehrere PDF-Dokumente zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Fügt mehrere Dokumentpfade zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Fügt mehrere Textdokumente zur Dokumentensammlung für die Zusammenfassungs-Copilot-Optionen hinzu. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Legt die Anweisungen für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Legt die maximalen Abschluss-Token für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Legt das Modell für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Legt die Zusammenfassungsaufforderung für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Legt die Temperatur für die Zusammenfassungs-Copilot-Optionen fest. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Legt den Top-P-Wert für die Zusammenfassungs-Copilot-Optionen fest. |

### Siehe auch

* Klasse [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* Schnittstelle [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)