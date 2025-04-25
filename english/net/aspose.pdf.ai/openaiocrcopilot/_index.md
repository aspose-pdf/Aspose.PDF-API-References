---
title: Class OpenAIOcrCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIOcrCopilot class. Provides OCR capabilities to extract text from PDF documents and images. The supported image types PNG .png JPEG .jpeg and .jpg WEBP .webp nonanimated GIF .gif. Example usage of creating an OpenAI client configuring options and using the OCR copilot
type: docs
weight: 980
url: /net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Provides OCR capabilities to extract text from PDF documents and images. The supported image types: PNG (.png), JPEG (.jpeg and .jpg), WEBP (.webp), non-animated GIF (.gif). Example usage of creating an OpenAI client, configuring options, and using the OCR copilot.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Configure optional parameters.
    .Build(); // Build

// Create copilot options.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...create using delegate.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Create summary copilot.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Get text recognitions.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Access to the extracted text.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Initializes a new instance of the `OpenAIOcrCopilot` class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### See Also

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


