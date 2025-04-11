---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest 类。表示创建线程并在一个请求中运行它的请求
type: docs
weight: 1070
url: /zh/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest 类

表示创建线程并在一个请求中运行它的请求。

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
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | 获取或设置用于执行此运行的助手的 ID。 |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | 获取或设置覆盖助手指令的指令。这对于按运行修改行为非常有用。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | 获取或设置在运行过程中可能使用的最大完成令牌数。运行将尽力仅使用指定数量的完成令牌，跨多个回合。如果运行超过指定的完成令牌数，运行将以状态不完整结束。有关更多信息，请参见 incomplete_details。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | 获取或设置在运行过程中可能使用的最大提示令牌数。运行将尽力仅使用指定数量的提示令牌，跨多个回合。如果运行超过指定的提示令牌数，运行将以状态不完整结束。有关更多信息，请参见 incomplete_details。 |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | 获取或设置可以附加到对象的一组 16 个键值对。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | 获取或设置用于执行此运行的模型 ID。如果在此处提供值，它将覆盖与助手关联的模型。如果没有，将使用与助手关联的模型。 |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 和自 gpt-3.5-turbo-1106 以来的所有 GPT-3.5 Turbo 模型兼容。设置为 { "type": "json_object" } 启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，您还必须通过系统或用户消息指示模型生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行且似乎“卡住”。还请注意，如果 finish_reason="length"，消息内容可能会部分被截断，这表示生成超过了 max_tokens 或对话超过了最大上下文长度。 |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | 获取或设置是否使用流。如果为 true，则返回在运行过程中发生的事件流作为服务器发送的事件，当运行进入终止状态时以数据: [DONE] 消息终止。 |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | 获取或设置要使用的采样温度，范围在 0 到 2 之间。较高的值如 0.8 会使输出更随机，而较低的值如 0.2 会使其更集中和确定。 |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | 获取或设置创建线程的请求。 |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | 获取或设置模型调用的工具（如果有的话）。none 表示模型不会调用任何工具，而是生成消息。auto 是默认值，表示模型可以选择生成消息或调用一个或多个工具。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具如 {"type": "file_search"} 或 {"type": "function", "function": {"name": "my_function"}} 强制模型调用该工具。 |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | 获取或设置助手工具使用的一组资源。 |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | 获取或设置覆盖助手可以用于此运行的工具。这对于按运行修改行为非常有用。 |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | 获取或设置一个值，作为使用温度采样的替代，称为核采样，其中模型考虑具有 top_p 概率质量的令牌的结果。因此 0.1 意味着仅考虑组成前 10% 概率质量的令牌。我们通常建议更改此值或温度，但不同时更改两者。 |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | 获取或设置控制线程在运行之前如何被截断的截断策略。使用此选项控制运行的初始上下文窗口。 |

### 另请参见

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)