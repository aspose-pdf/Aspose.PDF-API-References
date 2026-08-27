---
title: "Classe OpenAIOcrCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.OpenAIOcrCopilot. Fornisce funzionalità OCR per estrarre testo da documenti PDF e immagini. I tipi di immagine supportati sono PNG .png, JPEG .jpeg e .jpg, WEBP .webp, GIF non animata .gif. Esempio di utilizzo per creare un client OpenAI configurando le opzioni e usando il copilot OCR"
type: docs
weight: 980
url: /it/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Fornisce capacità OCR per estrarre testo da documenti PDF e immagini. I tipi di immagine supportati: PNG (.png), JPEG (.jpeg e .jpg), WEBP (.webp), GIF non animata (.gif). Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il copilot OCR.

```csharp
// Crea client AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization(\"org_123\") // Configura parametri opzionali.
    .Build(); // Build

// Crea opzioni per il copilot.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...crea usando il delegato.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Crea copilot di riepilogo.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Ottieni riconoscimenti di testo.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Accesso al testo estratto.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Inizializza una nuova istanza della classe `OpenAIOcrCopilot`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Vedi anche

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


