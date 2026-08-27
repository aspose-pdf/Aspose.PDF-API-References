---
title: "الفئة OpenAIImageDescriptionCopilot"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. توفر وظائف معالجة الصور لفئة OpenAICopilot. مثال على استخدام إنشاء تكوين عميل OpenAI لخيارات ImageDescriptionCopilot واستخدام المساعد لتوليد أوصاف الصور وإضافة الأوصاف إلى المستندات المرفقة."
type: docs
weight: 940
url: /ar/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

يوفر وظائف معالجة الصور لفئة OpenAICopilot. مثال على الاستخدام لإنشاء عميل OpenAI، وتكوين خيارات ImageDescriptionCopilot، واستخدام المساعد لتوليد أوصاف الصور وإضافة أوصاف إلى المستندات المرفقة.

```csharp
// إنشاء عميل الذكاء الاصطناعي.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// إنشاء خيارات المساعد.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...إنشاء باستخدام المُفوض.
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

// إنشاء المساعد.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// احصل على أوصاف الصور.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// استخدم طريقة الامتداد لإضافة أوصاف الصور إلى المستندات المرفقة.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | يُهيئ مثيلاً جديداً من الفئة `OpenAIImageDescriptionCopilot`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### انظر أيضًا

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


