---
title: "Klass OpenAIChatCopilotOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIChatCopilotOptions-klass. Representerar alternativen för att konfigurera OpenAICopilot"
type: docs
weight: 890
url: /sv/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions class

Representerar alternativen för att konfigurera OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Hämtar eller anger namnet på assistenten. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Hämtar eller anger filsökvägen för kontextens backup-JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller anger samlingen av dokument som ska bearbetas. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet slutförandetoken som kan användas under körningen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/maxprompttokens/) { get; set; } | Hämtar eller anger det maximala antalet prompt‑token som kan användas under körningen. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Hämtar eller anger modellen som ska användas för assistenten. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Hämtar eller anger ett värde som indikerar om kontexten ska återställas från backup. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller anger filsökvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Hämtar eller anger samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Hämtar eller anger top‑p‑värdet för kärnsampling. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Hämtar eller anger trunkeringsstrategin för tråden. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Hämtar eller anger antalet dagar innan vektorlageret löper ut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Skapar en ny instans av `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Skapar en instans av `OpenAIChatCopilotOptions` och konfigurerar den med den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Hämtar den aktuella `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Anger assistentnamnet för chattcopilot-alternativen. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Anger filsökvägen för kontextens backup-JSON i chattcopilot-alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF-dokument i dokumentsamlingen för chattcopilot-alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Lägger till en dokumentväg i dokumentsamlingen för chattcopilot-alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Lägger till ett textdokument i dokumentsamlingen för chattcopilot-alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Ställer in dokumentsamlingen för chat copilot-alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentsamlingen för chat copilot-alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Lägger till flera dokumentsökvägar i dokumentsamlingen för chat copilot-alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Lägger till flera textdokument i dokumentsamlingen för chat copilot-alternativen. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Ställer in instruktionerna för chat copilot-alternativen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Ställer in maximala slutförandetoken för chat copilot-alternativen. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Ställer in maximala prompt‑token för chat copilot-alternativen. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Ställer in modellen för chat copilot-alternativen. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Ställer in om kontexten ska återställas från säkerhetskopia i chat copilot-alternativen. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Ställer in temperaturen för chat copilot-alternativen. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Ställer in top‑P‑värdet för chat copilot-alternativen. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Ställer in trunkeringsstrategin för chat copilot-alternativen. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Ställer in antalet dagar för utgång av vektorlager i chat copilot-alternativen. |

### Se även

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


