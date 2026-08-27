---
title: "Klass OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot-klass. Tillhandahåller bildbehandlingsfunktionalitet för OpenAICopilot‑klassen. Exempel på användning för att skapa en OpenAI‑klientkonfiguration av ImageDescriptionCopilot‑alternativ och användning av copilot för att generera bildbeskrivningar och lägga till beskrivningar till bifogade dokument"
type: docs
weight: 940
url: /sv/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

Tillhandahåller bildbehandlingsfunktionalitet för OpenAICopilot‑klassen. Exempel på användning av att skapa en OpenAI‑klient, konfigurering av ImageDescriptionCopilot‑alternativ och användning av copilot för att generera bildbeskrivningar samt lägga till beskrivningar i bifogade dokument.

```csharp
// Skapa AI‑klient.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Skapa copilot‑alternativ.
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

// Skapa copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Hämta bildbeskrivningar.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Använd förlängningsmetod för att lägga till bildbeskrivningar till bifogade dokument.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Initierar en ny instans av klassen `OpenAIImageDescriptionCopilot`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Se även

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


