---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Предоставляет функциональность обработки изображений для класса OpenAICopilot. Пример использования создания конфигурации клиента OpenAI с параметрами ImageDescriptionCopilot и использования копилота для генерации описаний изображений и добавления описаний к прикрепленным документам.
type: docs
weight: 880
url: /ru/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## Класс OpenAIImageDescriptionCopilot

Предоставляет функциональность обработки изображений для класса OpenAICopilot. Пример использования создания клиента OpenAI, конфигурации параметров ImageDescriptionCopilot и использования копилота для генерации описаний изображений и добавления описаний к прикрепленным документам.

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

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Инициализирует новый экземпляр класса `OpenAIImageDescriptionCopilot`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### См. также

* интерфейс [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)