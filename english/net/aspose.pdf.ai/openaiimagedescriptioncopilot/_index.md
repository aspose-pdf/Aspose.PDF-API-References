---
title: "OpenAIImageDescriptionCopilot Class"
linktitle: "OpenAIImageDescriptionCopilot"
articleTitle: "OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot class. Provides image processing functionality for OpenAICopilot class. Example usage of creating an OpenAI clien..."
type: docs
weight: 940
url: "/net/aspose.pdf.ai/openaiimagedescriptioncopilot/"
keywords: "OpenAIImageDescriptionCopilot, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## OpenAIImageDescriptionCopilot class

Provides image processing functionality for OpenAICopilot class. Example usage of creating an OpenAI client, configuration of ImageDescriptionCopilot options,
 and usage of the copilot to generate image descriptions and add descriptions to attached documents. 
 // Create AI client.
 var openAiClient = [OpenAIClient](../openaiclient/)
 .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
 .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
 .WithOrganization("org_123")
 .Build(); // Build. // Create copilot options.
 var options = [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
 .Create() // Create options like this, or...
 //.Create(options =&gt; { options.Model = [OpenAIModels](../openaimodels/).Gpt35Turbo; }) // ...create using delegate.
 .WithModel([OpenAIModels](../openaimodels/).Gpt35Turbo) // Configure other optional parameters.
 .WithTemperature(0.5)
 .WithTopP(1)
 .WithDocument(new [PdfDocument](../pdfdocument/) // Attach documents.
 {
 Name = "Another_Pdf_with_images",
 Document = new Document(GetInputPath("Pdf_with_images_low_res_bw.pdf"))
 })
 .WithDocument(GetInputPath("Mona_liza.jpg")) // Attach images
 .WithDocument(GetInputPath("Pdf_with_images.pdf")); // Attach document paths. // Create copilot.
 var copilot = [AICopilotFactory](../aicopilotfactory/).CreateImageDescriptionCopilot(openAiClient, options); // Get Image descriptions.
 List&lt;[ImageDescriptionResult](../imagedescriptionresult/)&gt; imageDescriptions = await copilot.GetImageDescriptionsAsync(); // Use extension method to add image descriptions to attached documents.
 await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Initializes a new instance of the `OpenAIImageDescriptionCopilot` class. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### See Also

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

