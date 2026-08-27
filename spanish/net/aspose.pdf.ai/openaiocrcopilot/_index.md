---
title: "Clase OpenAIOcrCopilot"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot class. Proporciona capacidades OCR para extraer texto de documentos PDF e imágenes. Los tipos de imagen compatibles PNG .png JPEG .jpeg y .jpg WEBP .webp GIF no animado .gif. Ejemplo de uso creando un cliente OpenAI, configurando opciones y usando el copilot OCR"
type: docs
weight: 980
url: /es/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Proporciona capacidades OCR para extraer texto de documentos PDF e imágenes. Los tipos de imagen compatibles: PNG (.png), JPEG (.jpeg y .jpg), WEBP (.webp), GIF no animado (.gif). Ejemplo de uso creando un cliente OpenAI, configurando opciones y usando el copilot OCR.

```csharp
// Crear cliente de IA.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Configura parámetros opcionales.
    .Build(); // Build

// Crear opciones del copilot.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...crea usando delegado.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Crear copilot de resumen.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Obtener reconocimientos de texto.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Acceso al texto extraído.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Inicializa una nueva instancia de la clase `OpenAIOcrCopilot`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Ver también

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


