---
title: "Klasse OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions-Klasse. Stellt die Optionen zur Konfiguration des OpenAIOcrCopilot dar."
type: docs
weight: 990
url: /de/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

Stellt die Optionen zur Konfiguration des OpenAIOcrCopilot dar.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | Liest oder legt das Detaillierungsniveau für die Bildanalyse fest. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Liest oder legt die Sammlung von documents fest, die verarbeitet werden sollen. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Liest oder legt die maximale Anzahl von Completion-Token fest, die während des Laufs verwendet werden können. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Liest oder legt das Modell fest, das für den Assistenten verwendet wird. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | Liest oder legt die Auflösung fest, die zum Konvertieren von PDF-Seiten in Bilder verwendet wird. Der Standardwert ist 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Liest oder legt den Dateipfad für die Textdatei fest, die die Systemanweisungen des Assistenten enthält. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Liest oder legt die Sampling-Temperatur fest, die für das Modell verwendet wird. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Liest oder legt den top-p-Wert für das Nucleus-Sampling fest. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | Liest oder legt die Benutzeraufforderung fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | Erstellt eine neue Instanz von `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | Erstellt eine Instanz von `OpenAIOcrCopilotOptions` und konfiguriert sie mit dem bereitgestellten Delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | Ruft die aktuelle `OpenAIOcrCopilotOptions` ab. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | Legt den Detaillierungsgrad für die Bildanalyse fest. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | Fügt ein PDF-Dokument zur Dokumentensammlung hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Fügt einen Dokumentpfad zur Dokumentensammlung hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Setzt die Dokumentensammlung. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Fügt mehrere PDF-Dokumente zur Dokumentensammlung hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Fügt mehrere Dokumentpfade zur Dokumentensammlung hinzu. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | Legt die maximale Anzahl an Completion-Token fest. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | Legt das Modell fest. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | Legt die Auflösung fest, die zum Konvertieren von PDF-Seiten in Bilder verwendet wird. Der Standardwert beträgt 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | Legt die Anweisungen für die OCR‑Copilot‑Optionen fest. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | Legt die Temperatur fest. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | Legt den Top‑P‑Wert fest. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | Legt die Benutzereingabe fest. |

### Siehe auch

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


