---
title: "Класс OpenAIOcrCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.OpenAIOcrCopilot. Предоставляет возможности OCR для извлечения текста из PDF‑документов и изображений. Поддерживаемые типы изображений: PNG .png, JPEG .jpeg и .jpg, WEBP .webp, неанимированный GIF .gif. Пример использования: создание клиента OpenAI, настройка параметров и использование OCR‑копилота."
type: docs
weight: 980
url: /ru/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Обеспечивает возможности OCR для извлечения текста из PDF Document и изображений. Поддерживаемые типы изображений: PNG (.png), JPEG (.jpeg и .jpg), WEBP (.webp), неанимированный GIF (.gif). Пример использования создания клиента OpenAI, настройки параметров и использования OCR‑копилота.

```csharp
// Создать AI‑клиент.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Настройте необязательные параметры.
    .Build(); // Build

// Создать параметры помощника.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...создать с использованием делегата.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Создать помощника резюме.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Получить распознавание текста.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Доступ к извлечённому тексту.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Инициализирует новый экземпляр класса `OpenAIOcrCopilot`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### См. также

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


