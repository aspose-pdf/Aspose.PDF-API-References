---
title: "LlamaSummaryCopilot Class"
linktitle: "LlamaSummaryCopilot"
articleTitle: "LlamaSummaryCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.LlamaSummaryCopilot class. Provides functionality for getting document summaries using AI models. Example usage of creating an Llama client, co..."
type: docs
weight: 790
url: "/net/aspose.pdf.ai/llamasummarycopilot/"
keywords: "LlamaSummaryCopilot, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## LlamaSummaryCopilot class

Provides functionality for getting document summaries using AI models. Example usage of creating an Llama client, configuring options, and using the summary copilot.
 Note: This copilot uses completion API, so the total amount of text that can be sent is limited by the model context window. 
 // Create AI client.
 var llamaClient = [LlamaClient](../llamaclient/)
 .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
 .Build(); // Create copilot options.
 var options = [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
 .Create() // Create options like this, or...
 //.Create(options =&gt; { options.Model = [LlamaModels](../llamamodels/).Llama13BChat; }) // ...create using delegate.
 .WithTemperature(0.5) // Configure other optional parameters.
 .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
 .WithDocuments(new List&lt;[TextDocument](../textdocument/)&gt;()); // .WithDocuments methods allows to add text, pdf and path collections. // Create summary copilot.
 var summaryCopilot = [AICopilotFactory](../aicopilotfactory/).CreateSummaryCopilot(llamaClient, options); // Get summary text.
 string summaryText = await summaryCopilot.GetSummaryAsync(); // Get summary document.
 Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync(); // Get summary document with page info.
 Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo()); // Save summary as PDF document.
 await summaryCopilot.SaveSummaryAsync("outputPath"); // Save summary with specified format.
 await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Initializes a new instance of the `LlamaSummaryCopilot` class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, SaveFormat, CancellationToken?) |  |

### See Also

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

