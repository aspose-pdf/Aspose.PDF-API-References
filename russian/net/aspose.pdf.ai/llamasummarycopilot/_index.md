---
title: "Класс LlamaSummaryCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.LlamaSummaryCopilot. Предоставляет функциональность для получения резюме документов с использованием AI‑моделей. Пример использования: создание клиента Llama, настройка параметров и использование помощника резюме. Примечание: этот помощник использует API завершения, поэтому общий объём текста, который можно отправить, ограничен контекстным окном модели."
type: docs
weight: 790
url: /ru/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

Предоставляет функциональность для получения резюме документов с использованием моделей ИИ. Пример использования: создание клиента Llama, настройка параметров и использование копилота резюме. Примечание: Этот копилот использует API завершения, поэтому общий объём текста, который можно отправить, ограничен контекстным окном модели.

```csharp
// Создать AI‑клиент.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Создать параметры помощника.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...создать с помощью делегата.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Создать помощника резюме.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

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
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Инициализирует новый экземпляр класса `LlamaSummaryCopilot`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### См. также

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


