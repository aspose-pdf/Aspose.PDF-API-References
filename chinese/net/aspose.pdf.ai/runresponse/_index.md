---
title: "类 RunResponse"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.RunResponse 类。表示在线程上的执行运行。"
type: docs
weight: 1100
url: /zh/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

表示在线程上的执行运行。

```csharp
public class RunResponse : BaseResponse, IStatus
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RunResponse](runresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | 获取或设置用于执行此运行的助手的 ID。 |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | 获取或设置运行被取消时的 Unix 时间戳（秒）。 |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | 获取或设置运行完成时的 Unix 时间戳（秒）。 |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | 获取或设置运行创建时的 Unix 时间戳（秒）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详情。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | 获取或设置运行将过期时的 Unix 时间戳（秒）。 |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | 获取或设置运行失败时的 Unix 时间戳（秒）。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | 获取或设置标识符，可在 API 端点中引用。 |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | 获取或设置运行不完整的原因详情。如果运行未不完整，则为 null。 |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | 获取或设置助手在此运行中使用的指令。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | 获取或设置与此运行关联的最后错误。如果没有错误，则为 null。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间已使用的最大完成令牌数。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | 获取或设置在运行期间已使用的最大提示令牌数。 |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息很有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | 获取或设置助手在此运行中使用的模型。 |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | 获取或设置对象类型，该类型始终为 thread.run。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | 获取或设置继续运行所需的操作细节。如果不需要任何操作，则为 null。 |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。兼容 GPT-4o、GPT-4 Turbo，以及自 gpt-3.5-turbo-1106 起的所有 GPT-3.5 Turbo 模型。将其设置为 { \"type\": \"json_object\" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，必须通过系统消息或用户消息指示模型自行生成 JSON。否则，模型可能会产生无限的空白流，直至生成达到 token 限制，导致请求长时间运行且看似“卡住”。另请注意，如果 finish_reason=\"length\"，消息内容可能会被部分截断，这表明生成超出了 max_tokens 或对话超出了最大上下文长度。 |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | 获取或设置运行开始时的 Unix 时间戳（秒）。 |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | 获取或设置运行的状态，可为 queued、in_progress、requires_action、cancelling、cancelled、failed、completed、incomplete 或 expired。 |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | 获取或设置此运行使用的采样温度。如果未设置，默认值为 1。 |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | 获取或设置作为此运行一部分执行的线程 ID。 |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | 获取或设置模型调用的工具（如果有）。none 表示模型不会调用任何工具，而是生成消息。auto 为默认值，表示模型可以在生成消息或调用一个或多个工具之间进行选择。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，例如 {\"type\": \"file_search\"} 或 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}，会强制模型调用该工具。 |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | 获取或设置助手在此运行中使用的工具列表。 |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | 获取或设置此运行使用的 nucleus 采样值。如果未设置，默认值为 1。 |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | 获取或设置截断策略，以控制线程在运行前如何被截断。可使用此设置来控制运行的初始上下文窗口。 |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | 获取或设置与运行相关的使用统计信息。如果运行未处于终止状态（例如 in_progress、queued 等），此值将为 null。 |

### 另请参见

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


