---
title: "类 OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot 类。为 OpenAICopilot 类提供图像处理功能。示例演示如何创建 ImageDescriptionCopilot 选项的 OpenAI 客户端配置，以及使用该副驾驶生成图像描述并将描述添加到附加文档中"
type: docs
weight: 940
url: /zh/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

为 OpenAICopilot 类提供图像处理功能。示例演示如何创建 OpenAI 客户端、配置 ImageDescriptionCopilot 选项，以及使用该副驾驶生成图像描述并将描述添加到附加的文档中。

```csharp
// 创建 AI 客户端。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// 创建副驾驶选项。
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...使用委托创建。
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

// 创建副驾驶。
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// 获取图像描述。
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// 使用扩展方法将图像描述添加到附加文档中。
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 初始化 `OpenAIImageDescriptionCopilot` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### 另请参见

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


