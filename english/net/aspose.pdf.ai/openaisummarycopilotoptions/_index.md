---
title: "OpenAISummaryCopilotOptions Class"
linktitle: "OpenAISummaryCopilotOptions"
articleTitle: "OpenAISummaryCopilotOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents the options for configuring the OpenAICopilot."
type: docs
weight: 1010
url: "/net/aspose.pdf.ai/openaisummarycopilotoptions/"
keywords: "OpenAISummaryCopilotOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAISummaryCopilotOptions class

Represents the options for configuring the OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase
```

## Properties

| Name | Description |
| --- | --- |
| [AssistantName](./assistantname/) { get; set; } | Gets or sets the name of the assistant. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Gets or sets the model to use for the assistant. *(Inherited from OpenAICopilotOptionsBase)* |
| [SummaryPrompt](./summaryprompt/) { get; set; } | Gets or sets the prompt to instruct the model to provide a document summary. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |

## Methods

| Name | Description |
| --- | --- |
| [Create](./create/) | Creates a new instance of [`OpenAISummaryCopilotOptions`](../../aspose.pdf.ai/openaisummarycopilotoptions/). |
| [Create](./create/)(*Action<OpenAISummaryCopilotOptions>*) | Creates an instance of [`OpenAISummaryCopilotOptions`](../../aspose.pdf.ai/openaisummarycopilotoptions/) and configures it using the provided delegate. |
| [GetOptions](./getoptions/) | Gets the current [`OpenAISummaryCopilotOptions`](../../aspose.pdf.ai/openaisummarycopilotoptions/). |
| [WithAssistantName](./withassistantname/)(*string*) | Sets the assistant name for the summary copilot options. |
| [WithDocument](./withdocument/)(*TextDocument*) | Adds a text document to the document collection for the summary copilot options. |
| [WithDocument](./withdocument/)(*PdfDocument*) | Adds a PDF document to the document collection for the summary copilot options. |
| [WithDocument](./withdocument/)(*string*) | Adds a document path to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(*DocumentCollection*) | Sets the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(*List<TextDocument>*) | Adds multiple text documents to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(*List<PdfDocument>*) | Adds multiple PDF documents to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(*List<string>*) | Adds multiple document paths to the document collection for the summary copilot options. |
| [WithInstructions](./withinstructions/)(*string*) | Sets the instructions for the summary copilot options. |
| [WithMaxCompletionTokens](./withmaxcompletiontokens/)(*Nullable<int>*) | Sets the max completion tokens for the summary copilot options. |
| [WithMaxPromptTokens](./withmaxprompttokens/)(*Nullable<int>*) | Sets the max prompt tokens for the summary copilot options. |
| [WithModel](./withmodel/)(*string*) | Sets the model for the summary copilot options. |
| [WithSummaryPrompt](./withsummaryprompt/)(*string*) | Sets the summary prompt for the summary copilot options. |
| [WithTemperature](./withtemperature/)(*Nullable<double>*) | Sets the temperature for the summary copilot options. |
| [WithTopP](./withtopp/)(*Nullable<double>*) | Sets the top P value for the summary copilot options. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

