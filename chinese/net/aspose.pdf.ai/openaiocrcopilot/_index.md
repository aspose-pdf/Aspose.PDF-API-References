---
title: "类 OpenAIOcrCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot 类。提供 OCR 功能以从 PDF Document 和图像中提取文本。支持的图像类型包括 PNG (.png)、JPEG (.jpeg 和 .jpg)、WEBP (.webp) 和非动画 GIF (.gif)。示例展示了创建 OpenAI 客户端、配置选项并使用 OCR copilot 的用法"
type: docs
weight: 980
url: /zh/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

提供 OCR 功能以从 PDF 文档和图像中提取文本。支持的图像类型：PNG（.png）、JPEG（.jpeg 和 .jpg）、WEBP（.webp）、非动画 GIF（.gif）。示例演示如何创建 OpenAI 客户端、配置选项并使用 OCR 副驾驶。

```csharp
// 创建 AI 客户端。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // 配置可选参数。
    .Build(); // Build

// 创建副驾驶选项。
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...使用委托创建。
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// 创建摘要副驾驶。
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// 获取文本识别结果。
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// 访问提取的文本。
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | 初始化 `OpenAIOcrCopilot` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### 另请参见

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


