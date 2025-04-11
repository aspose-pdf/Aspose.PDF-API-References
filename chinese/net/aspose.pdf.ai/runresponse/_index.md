---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse class. 表示线程上的执行运行
type: docs
weight: 1020
url: /zh/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

表示线程上的执行运行。

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [RunResponse](runresponse/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | 获取或设置用于执行此运行的助手的 ID。 |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | 获取或设置运行被取消时的 Unix 时间戳（以秒为单位）。 |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | 获取或设置运行完成时的 Unix 时间戳（以秒为单位）。 |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | 获取或设置运行创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | 获取或设置运行过期时的 Unix 时间戳（以秒为单位）。 |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | 获取或设置运行失败时的 Unix 时间戳（以秒为单位）。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | 获取或设置标识符，可以在 API 端点中引用。 |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | 获取或设置运行不完整的原因详细信息。如果运行不是不完整的，将为 null。 |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | 获取或设置助手用于此运行的指令。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | 获取或设置与此运行相关的最后一个错误。如果没有错误，将为 null。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | 获取或设置在运行过程中指定的最大完成令牌数。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | 获取或设置在运行过程中指定的最大提示令牌数。 |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | 获取或设置一组 16 个键值对，可以附加到对象上。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | 获取或设置助手用于此运行的模型。 |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | 获取或设置对象类型，始终为 thread.run。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | 获取或设置继续运行所需的操作详细信息。如果不需要任何操作，将为 null。 |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 和自 gpt-3.5-turbo-1106 以来的所有 GPT-3.5 Turbo 模型兼容。设置为 { "type": "json_object" } 启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，您还必须通过系统或用户消息指示模型生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行且似乎“卡住”。还请注意，如果 finish_reason="length"，消息内容可能会部分被截断，这表示生成超过了 max_tokens 或对话超过了最大上下文长度。 |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | 获取或设置运行开始时的 Unix 时间戳（以秒为单位）。 |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | 获取或设置运行状态，可以是 queued、in_progress、requires_action、cancelling、cancelled、failed、completed、incomplete 或 expired。 |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | 获取或设置此运行使用的采样温度。如果未设置，默认为 1。 |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | 获取或设置作为此运行一部分执行的线程的 ID。 |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | 获取或设置模型调用的工具（如果有）。none 表示模型不会调用任何工具，而是生成消息。auto 是默认值，表示模型可以选择生成消息或调用一个或多个工具。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，如 {"type": "file_search"} 或 {"type": "function", "function": {"name": "my_function"}} 强制模型调用该工具。 |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | 获取或设置助手用于此运行的工具列表。 |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | 获取或设置此运行使用的核采样值。如果未设置，默认为 1。 |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | 获取或设置控制线程在运行之前如何被截断的截断策略。使用此选项控制运行的初始上下文窗口。 |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | 获取或设置与运行相关的使用统计信息。如果运行不处于终止状态（即 in_progress、queued 等），则该值将为 null。 |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)