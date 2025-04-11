---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions-Klasse. Stellt die Optionen zur Konfiguration des OpenAICopilot dar
type: docs
weight: 900
url: /de/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions-Klasse

Stellt die Optionen zur Konfiguration des OpenAICopilot dar.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Ruft den Namen des Assistenten ab oder legt ihn fest. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ruft die Sammlung von Dokumenten ab oder legt sie fest, die verarbeitet werden sollen. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Ruft das Prompt ab oder legt es fest, um das Modell anzuweisen, eine Bildbeschreibung bereitzustellen. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Ruft die Detailstufe des Bildes ab oder legt sie fest, wenn sie vom Benutzer angegeben wird. "low" verwendet weniger Tokens, Sie können sich für eine hohe Auflösung mit "high" entscheiden. Wenn nicht festgelegt, wird standardmäßig "auto" verwendet. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Completion-Tokens ab, die im Verlauf des Laufs verwendet werden dürfen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Prompt-Tokens ab, die im Verlauf des Laufs verwendet werden dürfen. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Ruft das Vision-Modell ab oder legt es fest, das für den Assistenten verwendet werden soll. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ruft den Dateipfad für die Textdatei ab oder legt ihn fest, die die Systemanweisungen des Assistenten enthält. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ruft die Sampling-Temperatur ab oder legt sie fest, die für das Modell verwendet werden soll. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ruft den Top-P-Wert für die Kernstichprobe ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Erstellt eine neue Instanz von `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Erstellt eine Instanz von `OpenAIImageDescriptionCopilotOptions` und konfiguriert sie mit dem bereitgestellten Delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Ruft die aktuellen `OpenAIImageDescriptionCopilotOptions` ab. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Legt den Assistentennamen für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Fügt ein PDF-Dokument zur Dokumentensammlung für die Bildbeschreibung-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Fügt einen Dokumentpfad zur Dokumentensammlung für die Bildbeschreibung-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Legt die Dokumentensammlung für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Fügt mehrere PDF-Dokumente zur Dokumentensammlung für die Bildbeschreibung-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Fügt mehrere Dokumentpfade zur Dokumentensammlung für die Bildbeschreibung-Copilot-Optionen hinzu. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Legt das Prompt für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Legt die Detailstufe des Bildes fest. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Legt die Anweisungen für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Legt die maximalen Completion-Tokens für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Legt die maximalen Prompt-Tokens für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Legt das Modell für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Legt die Temperatur für die Bildbeschreibung-Copilot-Optionen fest. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Legt den Top-P-Wert für die Bildbeschreibung-Copilot-Optionen fest. |

### Siehe auch

* Klasse [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* Schnittstelle [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* Namensraum [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)