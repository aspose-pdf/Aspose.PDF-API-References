---
title: Class OpenAISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAISummaryCopilot class. Provides functionality for getting document summaries using AI models. Example usage of creating an OpenAI client configuring options and using the summary copilot
type: docs
weight: 920
url: /net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Provides functionality for getting document summaries using AI models. Example usage of creating an OpenAI client, configuring options, and using the summary copilot.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Create copilot options.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Create summary copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// Get summary text.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Get summary document.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Get summary document with page info.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Save summary as PDF document.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Save summary with specified format.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Initializes a new instance of the `OpenAISummaryCopilot` class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### See Also

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


