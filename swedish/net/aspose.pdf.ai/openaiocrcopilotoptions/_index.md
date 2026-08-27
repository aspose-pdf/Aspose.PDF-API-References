---
title: "Klass OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions-klass. Representerar alternativ för att konfigurera OpenAIOcrCopilot"
type: docs
weight: 990
url: /sv/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

Representerar alternativen för att konfigurera OpenAIOcrCopilot.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | Hämtar eller anger detaljnivån för bildanalys. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller anger samlingen av dokument som ska bearbetas. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet slutförandetoken som kan användas under körningen. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Hämtar eller anger modellen som ska användas för assistenten. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | Hämtar eller anger upplösningen som används för att konvertera PDF-sidor till bilder. Standardvärdet är 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller anger filsökvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Hämtar eller anger samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Hämtar eller anger top‑p‑värdet för kärnsampling. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | Hämtar eller anger användarens prompt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | Skapar en ny instans av `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | Skapar en instans av `OpenAIOcrCopilotOptions` och konfigurerar den med den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | Hämtar den aktuella `OpenAIOcrCopilotOptions`. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | Anger detaljnivån för bildanalys. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF-dokument i dokumentsamlingen. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Lägger till en dokumentväg i dokumentsamlingen. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Anger dokumentsamlingen. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentsamlingen. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Lägger till flera dokumentvägar i dokumentsamlingen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | Anger maximalt antal slutförandetoken. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | Anger modellen. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | Anger upplösningen som används för att konvertera PDF-sidor till bilder. Standardvärdet är 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | Anger instruktionerna för ocr copilot-alternativen. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | Ställer in temperaturen. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | Ställer in top P‑värdet. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | Ställer in användarens prompt. |

### Se även

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


