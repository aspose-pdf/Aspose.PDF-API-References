---
title: "Classe OpenAIImageDescriptionCopilot"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot classe. Fournit des fonctionnalités de traitement d'image pour la classe OpenAICopilot. Exemple d'utilisation pour créer une configuration client OpenAI des options ImageDescriptionCopilot et l'utilisation du copilote pour générer des descriptions d'images et ajouter des descriptions aux documents joints."
type: docs
weight: 940
url: /fr/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

Fournit des fonctionnalités de traitement d'image pour la classe OpenAICopilot. Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options ImageDescriptionCopilot et de l'utilisation du copilote pour générer des descriptions d'images et ajouter des descriptions aux documents joints.

```csharp
// Créer un client IA.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Créer des options de copilote.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...crée en utilisant un délégué.
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

// Créer le copilote.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Obtenir des descriptions d'images.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Utilisez la méthode d'extension pour ajouter des descriptions d'images aux documents joints.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Initialise une nouvelle instance de la classe `OpenAIImageDescriptionCopilot`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Voir aussi

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


