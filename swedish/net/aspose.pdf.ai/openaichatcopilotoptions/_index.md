---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIChatCopilotOptions klass. Representerar alternativen för att konfigurera OpenAICopilot
type: docs
weight: 830
url: /sv/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions klass

Representerar alternativen för att konfigurera OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Hämtar eller ställer in namnet på assistenten. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Hämtar eller ställer in filvägen för kontextbackup JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller ställer in samlingen av dokument som ska behandlas. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller ställer in det maximala antalet fullföljningstokens som kan användas under körningen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Hämtar eller ställer in det maximala antalet prompttokens som kan användas under körningen. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Hämtar eller ställer in modellen som ska användas för assistenten. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om kontexten ska återställas från backup. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller ställer in filvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Hämtar eller ställer in samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Hämtar eller ställer in top-p-värdet för kärnsampling. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Hämtar eller ställer in avkortningsstrategin för tråden. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Hämtar eller ställer in antalet dagar innan vektorbutiken går ut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Skapar en ny instans av `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Skapar en instans av `OpenAIChatCopilotOptions` och konfigurerar den med hjälp av den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Hämtar de aktuella `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Ställer in assistentens namn för chatcopilotalternativen. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Ställer in filvägen för kontextbackup JSON i chatcopilotalternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF-dokument i dokumentkollektionen för chatcopilotalternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Lägger till en dokumentväg i dokumentkollektionen för chatcopilotalternativen. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Lägger till ett textdokument i dokumentkollektionen för chatcopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Ställer in dokumentkollektionen för chatcopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentkollektionen för chatcopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Lägger till flera dokumentvägar i dokumentkollektionen för chatcopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Lägger till flera textdokument i dokumentkollektionen för chatcopilotalternativen. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Ställer in instruktionerna för chatcopilotalternativen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Ställer in max fullföljningstokens för chatcopilotalternativen. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Ställer in max prompttokens för chatcopilotalternativen. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Ställer in modellen för chatcopilotalternativen. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Ställer in om kontexten ska återställas från backup i chatcopilotalternativen. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Ställer in temperaturen för chatcopilotalternativen. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Ställer in top P-värdet för chatcopilotalternativen. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Ställer in avkortningsstrategin för chatcopilotalternativen. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Ställer in antalet dagar för vektorbutikens utgång i chatcopilotalternativen. |

### Se Även

* klass [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* gränssnitt [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)