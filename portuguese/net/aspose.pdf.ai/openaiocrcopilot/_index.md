---
title: "Classe OpenAIOcrCopilot"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Classe Aspose.Pdf.AI.OpenAIOcrCopilot. Fornece recursos de OCR para extrair texto de documentos PDF e imagens. Os tipos de imagem suportados são PNG .png, JPEG .jpeg e .jpg, WEBP .webp, GIF não animado .gif. Exemplo de uso criando um cliente OpenAI, configurando opções e usando o copilot OCR."
type: docs
weight: 980
url: /pt/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Fornece recursos de OCR para extrair texto de documentos PDF e imagens. Os tipos de imagem suportados: PNG (.png), JPEG (.jpeg e .jpg), WEBP (.webp), GIF não animado (.gif). Exemplo de uso criando um cliente OpenAI, configurando opções e usando o copilot OCR.

```csharp
// Crie o cliente de IA.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Configura parâmetros opcionais.
    .Build(); // Build

// Crie as opções do copilot.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...cria usando delegate.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Crie o copilot de resumo.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Obtenha reconhecimentos de texto.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Acesso ao texto extraído.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Inicializa uma nova instância da classe `OpenAIOcrCopilot`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Veja Também

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


