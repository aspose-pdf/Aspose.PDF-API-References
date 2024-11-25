---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions class. Represents the options for configuring the OpenAICopilot
type: docs
weight: 900
url: /net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
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
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Gets or sets the name of the assistant. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Gets or sets the prompt to instruct the model to provide image description. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Gets or sets the detail level of the image if specified by the user. "low" uses fewer tokens, you can opt in to high resolution using "high". If not set defaults to "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Gets or sets the vision model to use for the assistant. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Creates a new instance of `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Creates an instance of `OpenAIImageDescriptionCopilotOptions` and configures it using the provided delegate. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Gets the current `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Sets the assistant name for the image description copilot options. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Adds a PDF document to the document collection for the image description copilot options. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Adds a document path to the document collection for the image description copilot options. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Sets the document collection for the image description copilot options. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Adds multiple PDF documents to the document collection for the image description copilot options. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Adds multiple document paths to the document collection for the image description copilot options. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Sets the prompt for the image description copilot options. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Sets the image detail level. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Sets the instructions for the image description copilot options. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Sets the max completion tokens for the image description copilot options. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Sets the max prompt tokens for the image description copilot options. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Sets the model for the image description copilot options. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Sets the temperature for the image description copilot options. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Sets the top P value for the image description copilot options. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


