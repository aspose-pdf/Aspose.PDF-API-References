---
title: "Класс OpenAISummaryCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot class. Предоставляет функциональность получения резюме документов с использованием AI‑моделей. Пример использования при создании клиента OpenAI, настройке параметров и использовании копилота для создания резюме."
type: docs
weight: 1000
url: /ru/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Предоставляет функциональность получения резюме Document с использованием моделей ИИ. Пример использования создания клиента OpenAI, настройки параметров и использования summary‑копилота.

```csharp
// Создать AI‑клиент.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Создать параметры помощника.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...создать с помощью делегата.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Создать помощника резюме.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// Получить текст резюме.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Получить документ резюме.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Получить документ резюме с информацией о страницах.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Сохранить резюме как PDF‑документ.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Сохранить резюме в указанном формате.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Инициализирует новый экземпляр класса `OpenAISummaryCopilot`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### См. также

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


