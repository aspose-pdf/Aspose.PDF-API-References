---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Proporciona funcionalidad de procesamiento de imágenes para la clase OpenAICopilot. Ejemplo de uso de la creación de una configuración de cliente OpenAI de opciones de ImageDescriptionCopilot y uso del copiloto para generar descripciones de imágenes y agregar descripciones a documentos adjuntos.
type: docs
weight: 880
url: /es/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## Clase OpenAIImageDescriptionCopilot

Proporciona funcionalidad de procesamiento de imágenes para la clase OpenAICopilot. Ejemplo de uso de la creación de un cliente OpenAI, configuración de opciones de ImageDescriptionCopilot y uso del copiloto para generar descripciones de imágenes y agregar descripciones a documentos adjuntos.

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

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Inicializa una nueva instancia de la clase `OpenAIImageDescriptionCopilot`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Véase también

* interfaz [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)