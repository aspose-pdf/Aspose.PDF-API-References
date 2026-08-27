---
title: "类 AssistantModifyRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.AssistantModifyRequest 类。用于修改助手的请求对象"
type: docs
weight: 130
url: /zh/net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest class

用于修改助手的请求对象。

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | 获取或设置助手的描述。最大长度为 512 个字符。 |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | 获取或设置助手使用的系统指令。最大长度为 256,000 个字符。 |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息很有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | 获取或设置要使用的模型 ID。您可以使用列出模型的 API 查看所有可用模型，或查阅我们的模型概览获取模型描述。 |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | 获取或设置助手的名称。最大长度为 256 个字符。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。兼容 GPT-4o、GPT-4 Turbo，以及自 gpt-3.5-turbo-1106 起的所有 GPT-3.5 Turbo 模型。将其设置为 { "type": "json_object" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，您还必须通过系统消息或用户消息指示模型自行生成 JSON。否则，模型可能会产生无限的空白流，直至生成达到 token 限制，导致请求长时间运行且看似"卡住"。另外请注意，如果 finish_reason="length"，消息内容可能会被部分截断，这表明生成超出了 max_tokens 或对话超出了最大上下文长度。 |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | 获取或设置使用的采样温度，范围在 0 到 2 之间。较高的值（如 0.8）会使输出更随机，而较低的值（如 0.2）会使输出更集中且确定。 |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | 获取或设置助手工具使用的资源。资源特定于工具类型。例如，code_interpreter 工具需要文件 ID 列表，而 file_search 工具需要向量存储 ID 列表。 |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | 获取或设置在助手上启用的工具列表。每个助手最多可启用 128 个工具。工具类型可以是 code_interpreter、file_search 或 function。 |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | 获取或设置温度采样的替代方案，称为 nucleus 采样，即模型根据 top_p 概率质量考虑 token 的结果。因此 0.1 表示仅考虑占前 10% 概率质量的 token。我们通常建议只调整其中之一，而不是同时修改两者。 |

### 另请参见

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


