---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantCreateRequest 类。用于创建助手的请求对象
type: docs
weight: 100
url: /zh/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest 类

用于创建助手的请求对象。

```csharp
public class AssistantCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | 获取或设置助手的描述。最大长度为 512 个字符。 |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | 获取或设置助手使用的系统指令。最大长度为 256,000 个字符。 |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | 获取或设置可以附加到对象的一组 16 个键值对。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | 获取或设置要使用的模型 ID。您可以使用列表模型 API 查看所有可用模型，或查看我们的模型概述以获取描述。 |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | 获取或设置助手的名称。最大长度为 256 个字符。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 和自 gpt-3.5-turbo-1106 以来的所有 GPT-3.5 Turbo 模型兼容。设置为 { "type": "json_object" } 启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，您还必须通过系统或用户消息指示模型生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行且似乎“卡住”。还请注意，如果 finish_reason="length"，消息内容可能会部分被截断，这表示生成超出了 max_tokens 或对话超出了最大上下文长度。 |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | 获取或设置要使用的采样温度，范围在 0 到 2 之间。较高的值如 0.8 会使输出更随机，而较低的值如 0.2 会使其更集中和确定。 |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | 获取或设置助手工具使用的资源。这些资源特定于工具的类型。例如，code_interpreter 工具需要文件 ID 列表，而 file_search 工具需要向量存储 ID 列表。 |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | 获取或设置助手启用的工具列表。每个助手最多可以有 128 个工具。工具可以是 code_interpreter、file_search 或 function 类型。 |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | 获取或设置一种替代温度采样的方法，称为核采样，其中模型考虑具有 top_p 概率质量的令牌结果。因此 0.1 意味着仅考虑组成前 10% 概率质量的令牌。我们通常建议更改此项或温度，但不要同时更改两者。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)