---
title: "OpenAISummaryCopilot Class"
linktitle: "OpenAISummaryCopilot"
articleTitle: "OpenAISummaryCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot class. Provides functionality for getting document summaries using AI models. Example usage of creating an OpenAI client, ..."
type: docs
weight: 1000
url: "/net/aspose.pdf.ai/openaisummarycopilot/"
keywords: "OpenAISummaryCopilot, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## OpenAISummaryCopilot class

Provides functionality for getting document summaries using AI models. Example usage of creating an OpenAI client, configuring options, and using the summary copilot. 
 // Create AI client.
 var openAiClient = [OpenAIClient](../openaiclient/)
 .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
 .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
 .Build(); // Create copilot options.
 var options = [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
 .Create() // Create options like this, or...
 //.Create(options =&gt; { options.Model = [OpenAIModels](../openaimodels/).Gpt35Turbo; }) // ...create using delegate.
 .WithTemperature(0.5) // Configure other optional parameters.
 .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
 .WithDocuments(new List&lt;[TextDocument](../textdocument/)&gt;()); // .WithDocuments methods allows to add text, pdf and path collections. // Create summary copilot.
 var summaryCopilot = [AICopilotFactory](../aicopilotfactory/).CreateSummaryCopilot(openAiClient, options); // Get summary text.
 string summaryText = await summaryCopilot.GetSummaryAsync(); // Get summary document.
 Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync(); // Get summary document with page info.
 Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo()); // Save summary as PDF document.
 await summaryCopilot.SaveSummaryAsync("outputPath"); // Save summary with specified format.
 await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Initializes a new instance of the `OpenAISummaryCopilot` class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, SaveFormat, CancellationToken?) |  |

### See Also

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

