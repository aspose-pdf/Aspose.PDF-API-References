---
title: "Classe OpenAIOcrCopilot"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.OpenAIOcrCopilot. Fournit des capacités OCR pour extraire du texte des documents PDF et des images. Les types d'image pris en charge sont PNG .png, JPEG .jpeg et .jpg, WEBP .webp, GIF non animé .gif. Exemple d'utilisation pour créer un client OpenAI, configurer les options et utiliser le copilote OCR"
type: docs
weight: 980
url: /fr/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Fournit des capacités OCR pour extraire du texte des documents PDF et des images. Les types d'image pris en charge : PNG (.png), JPEG (.jpeg et .jpg), WEBP (.webp), GIF non animé (.gif). Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options et de l'utilisation du copilote OCR.

```csharp
// Créer un client IA.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Configurer les paramètres optionnels.
    .Build(); // Build

// Créer des options de copilote.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...créer en utilisant le délégué.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Créer le copilote de résumé.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Obtenir les reconnaissances de texte.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Accès au texte extrait.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Initialise une nouvelle instance de la classe `OpenAIOcrCopilot`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Voir aussi

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


