---
title: "الفئة OpenAIOcrCopilot"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIOcrCopilot. توفر إمكانيات OCR لاستخراج النص من مستندات PDF والصور. أنواع الصور المدعومة PNG .png JPEG .jpeg و .jpg WEBP .webp GIF غير المتحركة .gif. مثال على استخدام إنشاء عميل OpenAI وتكوين الخيارات واستخدام مساعد OCR."
type: docs
weight: 980
url: /ar/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

يوفر قدرات OCR لاستخراج النص من مستندات PDF والصور. أنواع الصور المدعومة: PNG (.png)، JPEG (.jpeg و .jpg)، WEBP (.webp)، GIF غير المتحرك (.gif). مثال على الاستخدام لإنشاء عميل OpenAI، وتكوين الخيارات، واستخدام مساعد OCR.

```csharp
// إنشاء عميل الذكاء الاصطناعي.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization(\"org_123\") // تكوين المعلمات الاختيارية.
    .Build(); // Build

// إنشاء خيارات المساعد.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...إنشاء باستخدام المفوض.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// إنشاء مساعد الملخص.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// احصل على التعرف على النص.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// الوصول إلى النص المستخرج.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | يُهيئ مثيلاً جديداً من الفئة `OpenAIOcrCopilot`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### انظر أيضًا

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


