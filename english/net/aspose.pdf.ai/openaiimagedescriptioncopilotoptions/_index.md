---
title: "OpenAIImageDescriptionCopilotOptions Class"
linktitle: "OpenAIImageDescriptionCopilotOptions"
articleTitle: "OpenAIImageDescriptionCopilotOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions class. Represents the options for configuring the OpenAICopilot."
type: docs
weight: 960
url: "/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/"
keywords: "OpenAIImageDescriptionCopilotOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIImageDescriptionCopilotOptions class

Represents the options for configuring the OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [AssistantName](./assistantname/) { get; set; } | Gets or sets the name of the assistant. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. |
| [ImageDescriptionPrompt](./imagedescriptionprompt/) { get; set; } | Gets or sets the prompt to instruct the model to provide image description. |
| [ImageDetail](./imagedetail/) { get; set; } | Gets or sets the detail level of the image if specified by the user. "low" uses fewer tokens, you can opt in to high resolution using "high". If not set defaults to "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Gets or sets the model to use for the assistant. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](./create/)() | Creates a new instance of [`OpenAIImageDescriptionCopilotOptions`](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/). |
| static [Create](./create/)(Action<OpenAIImageDescriptionCopilotOptions>) | Creates an instance of [`OpenAIImageDescriptionCopilotOptions`](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/) and configures it using the provided delegate. |
| [GetOptions](./getoptions/)() | Gets the current [`OpenAIImageDescriptionCopilotOptions`](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/). |
| [WithAssistantName](./withassistantname/)(string) | Sets the assistant name for the image description copilot options. |
| [WithDocument](./withdocument/)(PdfDocument) | Adds a PDF document to the document collection for the image description copilot options. |
| [WithDocument](./withdocument/)(string) | Adds a document path to the document collection for the image description copilot options. |
| [WithDocuments](./withdocuments/)(DocumentCollection) | Sets the document collection for the image description copilot options. |
| [WithDocuments](./withdocuments/)(List<PdfDocument>) | Adds multiple PDF documents to the document collection for the image description copilot options. |
| [WithDocuments](./withdocuments/)(List<string>) | Adds multiple document paths to the document collection for the image description copilot options. |
| [WithImageDescriptionPrompt](./withimagedescriptionprompt/)(string) | Sets the prompt for the image description copilot options. |
| [WithImageDetail](./withimagedetail/)(string) | Sets the image detail level. |
| [WithInstructions](./withinstructions/)(string) | Sets the instructions for the image description copilot options. |
| [WithMaxCompletionTokens](./withmaxcompletiontokens/)(int?) | Sets the max completion tokens for the image description copilot options. |
| [WithMaxPromptTokens](./withmaxprompttokens/)(int?) | Sets the max prompt tokens for the image description copilot options. |
| [WithModel](./withmodel/)(string) | Sets the model for the image description copilot options. |
| [WithTemperature](./withtemperature/)(double?) | Sets the temperature for the image description copilot options. |
| [WithTopP](./withtopp/)(double?) | Sets the top P value for the image description copilot options. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

