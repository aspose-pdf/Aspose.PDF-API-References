---
title: "الفئة OpenAIChatCopilot"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIChatCopilot. تمثل مساعد دردشة للتفاعل مع المستندات عبر نماذج الذكاء الاصطناعي. مثال على استخدام إنشاء عميل OpenAI وتكوين الخيارات واستخدام ChatCopilot للتفاعل مع استفسارات المستخدم وإدارة سياق المحادثة."
type: docs
weight: 880
url: /ar/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

يمثل مساعد دردشة للتفاعل مع المستندات عبر نماذج الذكاء الاصطناعي. مثال على الاستخدام لإنشاء عميل OpenAI، وتكوين الخيارات، واستخدام ChatCopilot للتفاعل مع استفسارات المستخدم وإدارة سياق المحادثة.

```csharp
// إنشاء عميل الذكاء الاصطناعي.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// إنشاء خيارات المساعد.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...إنشاء باستخدام المُفوض.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// إنشاء مساعد الملخص.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// احصل على استجابة لاستعلام المستخدم.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// احصل على استجابة لقائمة الاستعلامات.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// حفظ الملخص كملف PDF.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// حفظ الملخص بالتنسيق المحدد.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// حفظ الملخص كملف PDF.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// حفظ الملخص بالتنسيق المحدد.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// احفظ السياق.
await chatCopilot.SaveContextAsync("outputPath");

// احذف السياق.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | يُنشئ مثيلاً جديدًا من الفئة `OpenAIChatCopilot` باستخدام العميل المحدد والخيارات. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### انظر أيضًا

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


