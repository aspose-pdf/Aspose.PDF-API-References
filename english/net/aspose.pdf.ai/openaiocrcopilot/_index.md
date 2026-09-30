---
title: "OpenAIOcrCopilot Class"
linktitle: "OpenAIOcrCopilot"
articleTitle: "OpenAIOcrCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot class. Provides OCR capabilities to extract text from PDF documents and images. The supported image types: PNG (.png), JPEG (...."
type: docs
weight: 980
url: "/net/aspose.pdf.ai/openaiocrcopilot/"
keywords: "OpenAIOcrCopilot, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIOcrCopilot class

Provides OCR capabilities to extract text from PDF documents and images.
 The supported image types: PNG (.png), JPEG (.jpeg and .jpg), WEBP (.webp), non-animated GIF (.gif).
 
 Example usage of creating an OpenAI client, configuring options, and using the OCR copilot.
 
 
 // Create AI client.
 var openAiClient = [OpenAIClient](../openaiclient/)
 .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
 //.WithOrganization("org_123") // Configure optional parameters.
 .Build(); // Build
 
 // Create copilot options.
 var options = [OpenAIOcrCopilotOptions](../openaiocrcopilotoptions/)
 .Create() // Create options like this, or...
 //.Create(options =&gt; { options.Model = [OpenAIModels](../openaimodels/).Gpt4O; }) // ...create using delegate.
 .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.
 
 // Create summary copilot.
 [IOcrCopilot](../iocrcopilot/) ocrCopilot = [AICopilotFactory](../aicopilotfactory/).CreateOcrCopilot(openAiClient, options);
 
 // Get text recognitions.
 List&lt;[TextRecognitionResult](../textrecognitionresult/)&gt; textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();
 
 // Access to the extracted text.
 string text = textRecognitions[0].OcrDetails[0].ExtractedText;

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAIOcrCopilot](./openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions<OpenAIOcrCopilotOptions>) | Initializes a new instance of the [`OpenAIOcrCopilot`](../../aspose.pdf.ai/openaiocrcopilot/) class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](./hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetTextRecognitionResultAsync](./gettextrecognitionresultasync/)(CancellationToken?) |  |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

