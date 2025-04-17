---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.LlamaSummaryCopilot. Предоставляет функциональность для получения резюме документов с использованием AI моделей. Пример использования создания клиента Llama, настройки параметров и использования помощника по резюме. Примечание Этот помощник использует API завершения, поэтому общее количество текста, которое можно отправить, ограничено контекстным окном модели.
type: docs
weight: 740
url: /ru/net/aspose.pdf.ai/llamasummarycopilot/
---
## Класс LlamaSummaryCopilot

Предоставляет функциональность для получения резюме документов с использованием AI моделей. Пример использования создания клиента Llama, настройки параметров и использования помощника по резюме. Примечание: Этот помощник использует API завершения, поэтому общее количество текста, которое можно отправить, ограничено контекстным окном модели.

```csharp
// Create AI client.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Create copilot options.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...create using delegate.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Create summary copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// Get summary text.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Get summary document.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Get summary document with page info.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Save summary as PDF document.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Save summary with specified format.
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

* интерфейс [ISummaryCopilot](../isummarycopilot/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)