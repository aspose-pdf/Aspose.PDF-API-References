---
title: "الفئة OpenAISummaryCopilot"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.OpenAISummaryCopilot. توفر وظائف للحصول على ملخصات المستندات باستخدام نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل OpenAI وتكوين الخيارات واستخدام المساعد الملخص."
type: docs
weight: 1000
url: /ar/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

يوفر وظائف للحصول على ملخصات المستندات باستخدام نماذج الذكاء الاصطناعي. مثال على الاستخدام لإنشاء عميل OpenAI، وتكوين الخيارات، واستخدام مساعد الملخص.

```csharp
// إنشاء عميل الذكاء الاصطناعي.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// إنشاء خيارات المساعد.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...إنشاء باستخدام المُفوض.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// إنشاء مساعد الملخص.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

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
public class OpenAISummaryCopilot : ISummaryCopilot
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | يُهيئ مثيلاً جديداً من الفئة `OpenAISummaryCopilot`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### انظر أيضًا

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


