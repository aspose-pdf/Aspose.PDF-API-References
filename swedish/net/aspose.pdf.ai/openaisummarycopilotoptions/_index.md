---
title: "Klass OpenAISummaryCopilotOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAISummaryCopilotOptions-klass. Representerar alternativen för att konfigurera OpenAICopilot"
type: docs
weight: 1010
url: /sv/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions class

Representerar alternativen för att konfigurera OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Hämtar eller anger namnet på assistenten. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller anger samlingen av dokument som ska bearbetas. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet slutförandetoken som kan användas under körningen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/maxprompttokens/) { get; set; } | Hämtar eller anger det maximala antalet prompt‑token som kan användas under körningen. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Hämtar eller anger modellen som ska användas för assistenten. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Hämtar eller anger prompten för att instruera modellen att leverera en dokumentsammanfattning. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller anger filsökvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Hämtar eller anger samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Hämtar eller anger top‑p‑värdet för kärnsampling. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | Skapar en ny instans av `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | Skapar en instans av `OpenAISummaryCopilotOptions` och konfigurerar den med den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Hämtar den aktuella `OpenAISummaryCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Anger assistentnamnet för sammanfattnings‑copilot‑alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF‑dokument i dokumentsamlingen för sammanfattnings‑copilot‑alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Lägger till en dokumentväg i dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Lägger till ett textdokument i dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Ställer in dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Lägger till flera dokumentvägar i dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Lägger till flera textdokument i dokumentsamlingen för alternativ för sammanfattnings‑copilot. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Ställer in instruktionerna för alternativ för sammanfattnings‑copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Ställer in maximalt antal token för slutförande för alternativ för sammanfattnings‑copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Ställer in maximalt antal token för prompt för alternativ för sammanfattnings‑copilot. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Ställer in modellen för alternativ för sammanfattnings‑copilot. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Ställer in sammanfattningsprompten för alternativ för sammanfattnings‑copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Ställer in temperaturen för alternativ för sammanfattnings‑copilot. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Ställer in top‑P‑värdet för alternativ för sammanfattnings‑copilot. |

### Se även

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


