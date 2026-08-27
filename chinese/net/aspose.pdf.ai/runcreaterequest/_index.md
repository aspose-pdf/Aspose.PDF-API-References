---
title: "类 RunCreateRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.RunCreateRequest 类。表示创建运行的请求"
type: docs
weight: 1060
url: /zh/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest class

表示创建运行的请求。

```csharp
public class RunCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | 获取或设置附加指令。将附加指令追加到运行指令的末尾。这对于在每次运行时修改行为而不覆盖其他指令非常有用。 |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | 获取或设置在创建运行之前发送到线程的附加消息。 |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | 获取或设置用于执行此运行的助手 ID。 |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | 获取或设置覆盖助手指令的说明。这对于在每次运行时修改行为很有用。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。运行将尽最大努力仅使用指定的完成标记数，跨多个回合。如果运行超过了指定的完成标记数，运行将以状态 incomplete 结束。有关更多信息，请参阅 incomplete_details。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | 获取或设置在运行期间可能使用的最大提示标记数。运行将尽最大努力仅使用指定的提示标记数，跨多个回合。如果运行超过了指定的提示标记数，运行将以状态 incomplete 结束。有关更多信息，请参阅 incomplete_details。 |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息很有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | 获取或设置用于执行此运行的模型 ID。如果在此提供了值，它将覆盖与助手关联的模型。如果未提供，将使用与助手关联的模型。 |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | 获取或设置响应格式。指定模型必须输出的格式。兼容 GPT-4o、GPT-4 Turbo，以及自 gpt-3.5-turbo-1106 起的所有 GPT-3.5 Turbo 模型。设置为 { "type": "json_object" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，必须通过系统消息或用户消息指示模型自行生成 JSON。否则，模型可能会生成无限的空白流，直到达到令牌限制，导致请求长时间运行并看似"卡住"。还需注意，如果 finish_reason="length"，消息内容可能会被截断，表示生成超出 max_tokens 或对话超出最大上下文长度。 |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | 获取或设置是否使用流式传输。如果为 true，则返回在运行期间发生的事件流，作为服务器发送事件（server‑sent events），并在运行进入终止状态并收到 data: [DONE] 消息时结束。 |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | 获取或设置使用的采样温度，范围在 0 到 2 之间。较高的值（如 0.8）会使输出更随机，而较低的值（如 0.2）会使输出更集中且确定。 |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | 获取或设置模型调用的工具（如果有）。none 表示模型不会调用任何工具，而是生成消息。auto 为默认值，表示模型可以在生成消息或调用一个或多个工具之间进行选择。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，例如 {\"type\": \"file_search\"} 或 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}，会强制模型调用该工具。 |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | 获取或设置覆盖助手在此运行中可使用的工具的工具。这对于按运行修改行为非常有用。 |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | 获取或设置温度采样的替代方案，称为 nucleus 采样，即模型根据 top_p 概率质量考虑 token 的结果。因此 0.1 表示仅考虑占前 10% 概率质量的 token。我们通常建议只调整其中之一，而不是同时修改两者。 |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | 获取或设置截断策略。控制线程在运行前如何被截断。使用此设置可控制运行的初始上下文窗口。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


