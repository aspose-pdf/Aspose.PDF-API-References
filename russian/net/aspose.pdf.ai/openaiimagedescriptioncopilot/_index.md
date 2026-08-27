---
title: "Класс OpenAIImageDescriptionCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot class. Предоставляет функциональность обработки изображений для класса OpenAICopilot. Пример использования при создании конфигурации клиента OpenAI с параметрами ImageDescriptionCopilot и использовании копилота для генерации описаний изображений и добавления описаний к прикреплённым документам"
type: docs
weight: 940
url: /ru/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

Предоставляет функциональность обработки изображений для класса OpenAICopilot. Пример использования создания клиента OpenAI, настройки параметров ImageDescriptionCopilot и использования копилота для генерации описаний изображений и добавления описаний к прикреплённым Document.

```csharp
// Создать AI‑клиент.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Создать параметры помощника.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...создать с помощью делегата.
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

// Создать копилот.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Получить описания изображений.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Использовать метод расширения для добавления описаний изображений к прикреплённым документам.
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

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


