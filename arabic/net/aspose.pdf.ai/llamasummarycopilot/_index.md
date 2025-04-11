---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.LlamaSummaryCopilot. توفر وظائف للحصول على ملخصات الوثائق باستخدام نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل Llama وتكوين الخيارات واستخدام مساعد الملخص. ملاحظة: يستخدم هذا المساعد واجهة برمجة التطبيقات للإكمال، لذا فإن إجمالي كمية النص التي يمكن إرسالها محدودة بواسطة نافذة سياق النموذج.
type: docs
weight: 740
url: /ar/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

توفر وظائف للحصول على ملخصات الوثائق باستخدام نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل Llama، وتكوين الخيارات، واستخدام مساعد الملخص. ملاحظة: يستخدم هذا المساعد واجهة برمجة التطبيقات للإكمال، لذا فإن إجمالي كمية النص التي يمكن إرسالها محدودة بواسطة نافذة سياق النموذج.

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

## Constructors

| Name | Description |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | يقوم بتهيئة مثيل جديد من فئة `LlamaSummaryCopilot`. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### See Also

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)