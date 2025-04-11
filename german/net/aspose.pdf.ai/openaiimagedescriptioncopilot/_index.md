---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilot-Klasse. Bietet Bildverarbeitungsfunktionen für die OpenAICopilot-Klasse. Beispiel für die Erstellung einer OpenAI-Clientkonfiguration der Optionen von ImageDescriptionCopilot und die Nutzung des Copiloten zur Generierung von Bildbeschreibungen und zum Hinzufügen von Beschreibungen zu angehängten Dokumenten
type: docs
weight: 880
url: /de/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot-Klasse

Bietet Bildverarbeitungsfunktionen für die OpenAICopilot-Klasse. Beispiel für die Erstellung eines OpenAI-Clients, die Konfiguration der Optionen von ImageDescriptionCopilot und die Nutzung des Copiloten zur Generierung von Bildbeschreibungen und zum Hinzufügen von Beschreibungen zu angehängten Dokumenten.

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

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Initialisiert eine neue Instanz der `OpenAIImageDescriptionCopilot`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Siehe auch

* Schnittstelle [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)