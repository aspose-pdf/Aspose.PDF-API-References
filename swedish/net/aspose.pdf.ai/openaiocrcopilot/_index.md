---
title: "Klass OpenAIOcrCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot‑klass. Tillhandahåller OCR‑funktioner för att extrahera text från PDF‑dokument och bilder. De stödjade bildtyperna är PNG .png, JPEG .jpeg och .jpg, WEBP .webp samt icke‑animerad GIF .gif. Exempel på hur man skapar en OpenAI‑klient, konfigurerar alternativ och använder OCR‑copiloten"
type: docs
weight: 980
url: /sv/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Tillhandahåller OCR‑funktioner för att extrahera text från PDF‑dokument och bilder. De stödda bildtyperna: PNG (.png), JPEG (.jpeg och .jpg), WEBP (.webp), icke‑animerad GIF (.gif). Exempel på användning av att skapa en OpenAI‑klient, konfigurera alternativ och använda OCR‑copilot.

```csharp
// Skapa AI‑klient.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Konfigurera valfria parametrar.
    .Build(); // Build

// Skapa copilot‑alternativ.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...skapa med delegat.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Skapa sammanfattnings‑copilot.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Hämta textigenkänningar.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Tillgång till den extraherade texten.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Initierar en ny instans av `OpenAIOcrCopilot`‑klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Se även

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


