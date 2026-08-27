---
title: "Klass OpenAIImageDescriptionCopilotOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions-klass. Representerar alternativen för att konfigurera OpenAICopilot."
type: docs
weight: 960
url: /sv/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

Representerar alternativen för att konfigurera OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Hämtar eller anger namnet på assistenten. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Hämtar eller anger samlingen av dokument som ska bearbetas. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Hämtar eller anger prompten för att instruera modellen att tillhandahålla bildbeskrivning. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Hämtar eller anger detaljnivån för bilden om den specificeras av användaren. \"low\" använder färre token, du kan välja hög upplösning med \"high\". Om den inte anges, är standardvärdet \"auto\". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet slutförandetoken som kan användas under körningen. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/maxprompttokens/) { get; set; } | Hämtar eller anger det maximala antalet prompt‑token som kan användas under körningen. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Hämtar eller anger modellen som ska användas för assistenten. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Hämtar eller anger filsökvägen för textfilen som innehåller assistentens systeminstruktioner. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Hämtar eller anger samplingstemperaturen som ska användas för modellen. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Hämtar eller anger top‑p‑värdet för kärnsampling. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Skapar en ny instans av `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Skapar en instans av `OpenAIImageDescriptionCopilotOptions` och konfigurerar den med den angivna delegaten. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Hämtar den aktuella `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Anger assistentnamnet för bildbeskrivnings‑copilot‑alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Lägger till ett PDF-dokument i dokumentsamlingen för bildbeskrivnings‑copilot‑alternativen. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Lägger till en dokumentväg i dokumentsamlingen för bildbeskrivnings‑copilot‑alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Anger dokumentsamlingen för bildbeskrivnings‑copilot‑alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Lägger till flera PDF-dokument i dokumentsamlingen för bildbeskrivnings‑copilot‑alternativen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Lägger till flera dokumentvägar i dokumentsamlingen för alternativen för bildbeskrivnings‑copilot. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Ställer in prompten för alternativen för bildbeskrivnings‑copilot. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Ställer in bildens detaljnivå. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Ställer in instruktionerna för alternativen för bildbeskrivnings‑copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Ställer in maximalt antal avslutningstoken för alternativen för bildbeskrivnings‑copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Ställer in maximalt antal prompt‑token för alternativen för bildbeskrivnings‑copilot. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Ställer in modellen för alternativen för bildbeskrivnings‑copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Ställer in temperaturen för alternativen för bildbeskrivnings‑copilot. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Ställer in top‑P‑värdet för alternativen för bildbeskrivnings‑copilot. |

### Se även

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


