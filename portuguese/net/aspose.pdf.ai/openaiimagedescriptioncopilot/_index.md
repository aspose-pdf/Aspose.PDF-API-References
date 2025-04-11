---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Fornece funcionalidade de processamento de imagem para a classe OpenAICopilot. Exemplo de uso da criação de uma configuração de cliente OpenAI das opções do ImageDescriptionCopilot e uso do copiloto para gerar descrições de imagens e adicionar descrições a documentos anexados.
type: docs
weight: 880
url: /pt/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## Classe OpenAIImageDescriptionCopilot

Fornece funcionalidade de processamento de imagem para a classe OpenAICopilot. Exemplo de uso da criação de um cliente OpenAI, configuração das opções do ImageDescriptionCopilot e uso do copiloto para gerar descrições de imagens e adicionar descrições a documentos anexados.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Create copilot options.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument(new PdfDocument // Attach documents.
    {
        Name = "Another_Pdf_with_images",
        Document = new Document(GetInputPath("Pdf_with_images_low_res_bw.pdf"))
    })
    .WithDocument(GetInputPath("Mona_liza.jpg")) // Attach images
    .WithDocument(GetInputPath("Pdf_with_images.pdf")); // Attach document paths.

// Create copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Get Image descriptions.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Use extension method to add image descriptions to attached documents.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Inicializa uma nova instância da classe `OpenAIImageDescriptionCopilot`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Veja Também

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)