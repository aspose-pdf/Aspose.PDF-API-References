---
title: "类 OpenAISummaryCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot 类。提供使用 AI 模型获取文档摘要的功能。示例演示了创建 OpenAI 客户端、配置选项并使用摘要副驾驶的用法。"
type: docs
weight: 1000
url: /zh/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

提供使用 AI 模型获取文档摘要的功能。示例演示如何创建 OpenAI 客户端、配置选项并使用 summary 副驾驶。

```csharp
// 创建 AI 客户端。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// 创建副驾驶选项。
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...使用委托创建。
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// 创建摘要副驾驶。
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// 获取摘要文本。
string summaryText = await summaryCopilot.GetSummaryAsync();

// 获取摘要文档。
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// 获取带有页面信息的摘要文档。
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// 将摘要保存为 PDF 文档。
await summaryCopilot.SaveSummaryAsync("outputPath");

// 使用指定格式保存摘要。
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | 初始化 `OpenAISummaryCopilot` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### 另请参见

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


