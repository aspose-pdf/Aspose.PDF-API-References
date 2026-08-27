---
title: "类 OpenAIChatCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIChatCopilot 类。表示用于通过 AI 模型与文档交互的聊天副驾驶。示例用法包括创建 OpenAI 客户端、配置选项以及使用 ChatCopilot 与用户查询交互并管理对话上下文。"
type: docs
weight: 880
url: /zh/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

表示用于通过 AI 模型与文档交互的聊天副驾驶。示例演示如何创建 OpenAI 客户端、配置选项，并使用 ChatCopilot 与用户查询交互以及管理对话上下文。

```csharp
// 创建 AI 客户端。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// 创建副驾驶选项。
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...使用委托创建。
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// 创建摘要副驾驶。
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// 获取用户查询的响应。
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// 获取查询列表的响应。
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// 将摘要保存为 PDF 文档。
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// 使用指定格式保存摘要。
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// 将摘要保存为 PDF 文档。
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// 使用指定格式保存摘要。
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// 保存上下文。
await chatCopilot.SaveContextAsync("outputPath");

// 删除上下文。
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 使用指定的客户端和选项初始化 `OpenAIChatCopilot` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### 另请参见

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


