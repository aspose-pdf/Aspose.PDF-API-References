---
title: "类 RunThreadCreateRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.RunThreadCreateRequest 类。表示在一次请求中创建线程并运行的请求"
type: docs
weight: 1150
url: /zh/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

表示创建线程并在一次请求中运行它的请求。

```csharp
public class RunThreadCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | 获取或设置用于执行此运行的助手 ID。 |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | 获取或设置覆盖助手指令的说明。这对于在每次运行时修改行为很有用。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。运行将尽最大努力仅使用指定的完成标记数，跨多个回合。如果运行超过了指定的完成标记数，运行将以状态 incomplete 结束。有关更多信息，请参阅 incomplete_details。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | 获取或设置在运行期间可能使用的最大提示标记数。运行将尽最大努力仅使用指定的提示标记数，跨多个回合。如果运行超过了指定的提示标记数，运行将以状态 incomplete 结束。有关更多信息，请参阅 incomplete_details。 |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | 获取或设置用于执行此运行的模型 ID。如果在此提供了值，它将覆盖与助手关联的模型。如果未提供，将使用与助手关联的模型。 |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。兼容 GPT-4o、GPT-4 Turbo，以及自 gpt-3.5-turbo-1106 起的所有 GPT-3.5 Turbo 模型。将其设置为 { \"type\": \"json_object\" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，必须通过系统消息或用户消息指示模型自行生成 JSON。否则，模型可能会产生无限的空白流，直至生成达到 token 限制，导致请求长时间运行且看似“卡住”。另请注意，如果 finish_reason=\"length\"，消息内容可能会被部分截断，这表明生成超出了 max_tokens 或对话超出了最大上下文长度。 |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | 获取或设置是否使用流式传输。如果为 true，则返回在运行期间发生的事件流，作为服务器发送事件（server‑sent events），并在运行进入终止状态并收到 data: [DONE] 消息时结束。 |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | 获取或设置使用的采样温度，范围在 0 到 2 之间。较高的值（如 0.8）会使输出更随机，而较低的值（如 0.2）会使输出更集中且确定。 |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | 获取或设置用于创建线程的请求。 |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | 获取或设置模型调用的工具（如果有）。none 表示模型不会调用任何工具，而是生成消息。auto 为默认值，表示模型可以在生成消息或调用一个或多个工具之间进行选择。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，例如 {\"type\": \"file_search\"} 或 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}，会强制模型调用该工具。 |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | 获取或设置助手工具使用的一组资源。 |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | 获取或设置覆盖助手在此运行中可使用的工具的工具。这对于按运行修改行为非常有用。 |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | 获取或设置一种替代温度采样的值，称为 nucleus 采样，其中模型考虑 top_p 概率质量的标记结果。因此 0.1 表示仅考虑占前 10% 概率质量的标记。我们通常建议仅修改此值或温度，而不是两者同时修改。 |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | 获取或设置截断策略，以控制线程在运行前如何被截断。可使用此设置来控制运行的初始上下文窗口。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


