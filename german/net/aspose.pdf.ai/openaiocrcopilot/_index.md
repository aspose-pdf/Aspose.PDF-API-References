---
title: "Klasse OpenAIOcrCopilot"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot‑Klasse. Bietet OCR‑Funktionen zum Extrahieren von Text aus PDF‑Dokumenten und Bildern. Unterstützte Bildtypen: PNG .png, JPEG .jpeg und .jpg, WEBP .webp, nicht animiertes GIF .gif. Beispielhafte Verwendung zum Erstellen eines OpenAI‑Clients, Konfigurieren von Optionen und Verwenden des OCR‑Copiloten."
type: docs
weight: 980
url: /de/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Bietet OCR‑Funktionen zum Extrahieren von Text aus PDF‑Dokumenten und Bildern. Unterstützte Bildtypen: PNG (.png), JPEG (.jpeg und .jpg), WEBP (.webp), nicht animiertes GIF (.gif). Beispielhafte Verwendung zum Erstellen eines OpenAI‑Clients, Konfigurieren von Optionen und Verwenden des OCR‑Copiloten.

```csharp
// Erstelle AI‑Client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Optionale Parameter konfigurieren.
    .Build(); // Build

// Erstelle Copilot‑Optionen.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...mit Delegat erstellen.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Erstelle Zusammenfassungs‑Copilot.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Hole Texterkennungen.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Zugriff auf den extrahierten Text.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Initialisiert eine neue Instanz der `OpenAIOcrCopilot`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Siehe auch

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


