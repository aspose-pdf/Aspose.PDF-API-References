---
title: "LlamaSummaryCopilotOptions Class"
linktitle: "LlamaSummaryCopilotOptions"
articleTitle: "LlamaSummaryCopilotOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.LlamaSummaryCopilotOptions class. Represents the options for configuring the OpenAICopilot."
type: docs
weight: 800
url: "/net/aspose.pdf.ai/llamasummarycopilotoptions/"
keywords: "LlamaSummaryCopilotOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## LlamaSummaryCopilotOptions class

Represents the options for configuring the OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Gets or sets the model to use for the assistant. |
| [SummaryPrompt](./summaryprompt/) { get; set; } | Gets or sets the prompt to instruct the model to provide a document summary. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](./create/)() | Creates a new instance of [`LlamaSummaryCopilotOptions`](../../aspose.pdf.ai/llamasummarycopilotoptions/). |
| static [Create](./create/)(Action<LlamaSummaryCopilotOptions>) | Creates an instance of [`LlamaSummaryCopilotOptions`](../../aspose.pdf.ai/llamasummarycopilotoptions/) and configures it using the provided delegate. |
| [GetOptions](./getoptions/)() | Gets the current [`LlamaSummaryCopilotOptions`](../../aspose.pdf.ai/llamasummarycopilotoptions/). |
| [WithDocument](./withdocument/)(PdfDocument) | Adds a PDF document to the document collection for the summary copilot options. |
| [WithDocument](./withdocument/)(string) | Adds a document path to the document collection for the summary copilot options. |
| [WithDocument](./withdocument/)(TextDocument) | Adds a text document to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(DocumentCollection) | Sets the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(List<PdfDocument>) | Adds multiple PDF documents to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(List<string>) | Adds multiple document paths to the document collection for the summary copilot options. |
| [WithDocuments](./withdocuments/)(List<TextDocument>) | Adds multiple text documents to the document collection for the summary copilot options. |
| [WithInstructions](./withinstructions/)(string) | Sets the instructions for the summary copilot options. |
| [WithMaxCompletionTokens](./withmaxcompletiontokens/)(int?) | Sets the max completion tokens for the summary copilot options. |
| [WithModel](./withmodel/)(string) | Sets the model for the summary copilot options. |
| [WithSummaryPrompt](./withsummaryprompt/)(string) | Sets the summary prompt for the summary copilot options. |
| [WithTemperature](./withtemperature/)(double?) | Sets the temperature for the summary copilot options. |
| [WithTopP](./withtopp/)(double?) | Sets the top P value for the summary copilot options. |

### See Also

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

