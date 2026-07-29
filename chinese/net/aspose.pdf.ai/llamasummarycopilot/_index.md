---
title: "类 LlamaSummaryCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.LlamaSummaryCopilot 类。提供使用 AI 模型获取文档摘要的功能。示例演示了创建 Llama 客户端、配置选项并使用摘要副驾驶。注意：此副驾驶使用完成 API，因此可发送的文本总量受模型上下文窗口的限制。"
type: docs
weight: 790
url: /zh/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

提供使用 AI 模型获取文档摘要的功能。示例包括创建 Llama 客户端、配置选项以及使用摘要 copilot。注意：此 copilot 使用 completion API，因此可发送的文本总量受模型上下文窗口的限制。

```csharp
// 创建 AI 客户端。
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// 创建副驾驶选项。
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // …使用委托创建。
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// 创建摘要副驾驶。
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

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
public class LlamaSummaryCopilot : ISummaryCopilot
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 初始化 `LlamaSummaryCopilot` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### 另请参见

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


