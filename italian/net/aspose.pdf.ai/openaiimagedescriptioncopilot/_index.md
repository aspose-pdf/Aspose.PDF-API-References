---
title: "Classe OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Fornisce funzionalità di elaborazione delle immagini per la classe OpenAICopilot. Esempio di utilizzo per creare una configurazione client OpenAI delle opzioni ImageDescriptionCopilot e l'uso del copilot per generare descrizioni delle immagini e aggiungere descrizioni ai documenti allegati."
type: docs
weight: 940
url: /it/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

Fornisce funzionalità di elaborazione immagini per la classe OpenAICopilot. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni di ImageDescriptionCopilot e utilizzare il copilot per generare descrizioni delle immagini e aggiungere descrizioni ai documenti allegati.

```csharp
// Crea client AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Crea opzioni per il copilot.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...crea usando il delegato.
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

// Crea copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Ottieni descrizioni delle immagini.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Usa il metodo di estensione per aggiungere descrizioni delle immagini ai documenti allegati.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Inizializza una nuova istanza della classe `OpenAIImageDescriptionCopilot`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Vedi anche

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


