---
title: "الفئة LlamaSummaryCopilot"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.AI.LlamaSummaryCopilot class. يوفر وظائف للحصول على ملخصات المستندات باستخدام نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل Llama وتكوين الخيارات واستخدام مساعد الملخص. ملاحظة: يستخدم هذا المساعد واجهة إكمال API لذا فإن الحد الأقصى لمقدار النص الذي يمكن إرساله محدود بنافذة سياق النموذج"
type: docs
weight: 790
url: /ar/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

يوفر وظائف للحصول على ملخصات المستندات باستخدام نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل Llama، وتكوين الخيارات، واستخدام مساعد الملخص. ملاحظة: يستخدم هذا المساعد واجهة إكمال، لذا فإن إجمالي النص الذي يمكن إرساله محدود بنافذة سياق النموذج.

```csharp
// إنشاء عميل الذكاء الاصطناعي.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// إنشاء خيارات المساعد.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...create using delegate.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// إنشاء مساعد الملخص.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// الحصول على نص الملخص.
string summaryText = await summaryCopilot.GetSummaryAsync();

// الحصول على مستند الملخص.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// الحصول على مستند الملخص مع معلومات الصفحة.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// حفظ الملخص كملف PDF.
await summaryCopilot.SaveSummaryAsync("outputPath");

// حفظ الملخص بالتنسيق المحدد.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | يُنشئ مثيلاً جديدًا من الفئة `LlamaSummaryCopilot`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### انظر أيضًا

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


