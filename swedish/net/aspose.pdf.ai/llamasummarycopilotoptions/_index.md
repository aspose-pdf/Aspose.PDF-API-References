---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilotOptions klass. Representerar alternativen för att konfigurera OpenAICopilot
type: docs
weight: 750
url: /sv/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions klass

Representerar alternativen för att konfigurera OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller ställer in samlingen av dokument som ska behandlas. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller ställer in det maximala antalet fullföljningstokens som kan användas under körningen. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Hämtar eller ställer in modellen som ska användas för assistenten. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Hämtar eller ställer in prompten för att instruera modellen att ge en dokument sammanfattning. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller ställer in filvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Hämtar eller ställer in samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Hämtar eller ställer in top-p-värdet för kärnsampling. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Skapar en ny instans av `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Skapar en instans av `LlamaSummaryCopilotOptions` och konfigurerar den med hjälp av den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Hämtar de aktuella `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF-dokument i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Lägger till en dokumentväg i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Lägger till ett textdokument i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Ställer in dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Lägger till flera dokumentvägar i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Lägger till flera textdokument i dokumentkollektionen för sammanfattningskopilotalternativen. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Ställer in instruktionerna för sammanfattningskopilotalternativen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Ställer in max fullföljningstokens för sammanfattningskopilotalternativen. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Ställer in modellen för sammanfattningskopilotalternativen. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Ställer in sammanfattningsprompten för sammanfattningskopilotalternativen. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Ställer in temperaturen för sammanfattningskopilotalternativen. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Ställer in top P-värdet för sammanfattningskopilotalternativen. |

### Se Även

* klass [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* gränssnitt [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)