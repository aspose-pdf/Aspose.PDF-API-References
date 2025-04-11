---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIChatCopilotOptions-Klasse. Stellt die Optionen zur Konfiguration des OpenAICopilot dar
type: docs
weight: 830
url: /de/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions-Klasse

Stellt die Optionen zur Konfiguration des OpenAICopilot dar.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Ruft den Namen des Assistenten ab oder legt ihn fest. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Ruft den Dateipfad für das Kontext-Backup-JSON ab oder legt ihn fest. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ruft die Sammlung von Dokumenten ab, die verarbeitet werden sollen, oder legt sie fest. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab, die während des Laufs verwendet werden dürfen, oder legt sie fest. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Eingabe-Token ab, die während des Laufs verwendet werden dürfen, oder legt sie fest. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Ruft das Modell ab, das für den Assistenten verwendet werden soll, oder legt es fest. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Kontext aus dem Backup wiederhergestellt werden soll. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ruft den Dateipfad für die Textdatei mit den Systemanweisungen des Assistenten ab oder legt ihn fest. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ruft die Sampling-Temperatur ab, die für das Modell verwendet werden soll, oder legt sie fest. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ruft den Top-P-Wert für die Kernstichprobe ab oder legt ihn fest. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Ruft die Trunkierungsstrategie für den Thread ab oder legt sie fest. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Ruft die Anzahl der Tage ab oder legt sie fest, bevor der Vektorstore abläuft. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Erstellt eine neue Instanz von `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Erstellt eine Instanz von `OpenAIChatCopilotOptions` und konfiguriert sie mit dem bereitgestellten Delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Ruft die aktuellen `OpenAIChatCopilotOptions` ab. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Legt den Assistentennamen für die Chat-Copilot-Optionen fest. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Legt den Dateipfad für das Kontext-Backup-JSON in den Chat-Copilot-Optionen fest. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Fügt ein PDF-Dokument zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Fügt einen Dokumentpfad zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Fügt ein Textdokument zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Legt die Dokumentensammlung für die Chat-Copilot-Optionen fest. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Fügt mehrere PDF-Dokumente zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Fügt mehrere Dokumentpfade zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Fügt mehrere Textdokumente zur Dokumentensammlung für die Chat-Copilot-Optionen hinzu. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Legt die Anweisungen für die Chat-Copilot-Optionen fest. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Legt die maximalen Abschluss-Token für die Chat-Copilot-Optionen fest. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Legt die maximalen Eingabe-Token für die Chat-Copilot-Optionen fest. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Legt das Modell für die Chat-Copilot-Optionen fest. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Legt fest, ob der Kontext aus dem Backup in den Chat-Copilot-Optionen wiederhergestellt werden soll. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Legt die Temperatur für die Chat-Copilot-Optionen fest. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Legt den Top-P-Wert für die Chat-Copilot-Optionen fest. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Legt die Trunkierungsstrategie für die Chat-Copilot-Optionen fest. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Legt die Anzahl der Tage für das Ablaufen des Vektorstores in den Chat-Copilot-Optionen fest. |

### Siehe auch

* Klasse [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* Schnittstelle [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)