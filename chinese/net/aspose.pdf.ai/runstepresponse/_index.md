---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse class. 表示运行执行中的一个步骤
type: docs
weight: 1060
url: /zh/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

表示运行执行中的一个步骤。

```csharp
public class RunStepResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | 获取或设置与运行步骤关联的助手的 ID。 |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | 获取或设置运行步骤被取消时的 Unix 时间戳（以秒为单位）。 |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | 获取或设置运行步骤完成时的 Unix 时间戳（以秒为单位）。 |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | 获取或设置运行步骤创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | 获取或设置运行步骤过期时的 Unix 时间戳（以秒为单位）。如果父运行过期，则步骤被视为过期。 |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | 获取或设置运行步骤失败时的 Unix 时间戳（以秒为单位）。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | 获取或设置运行步骤的标识符，可以在 API 端点中引用。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | 获取或设置与此运行步骤关联的最后一个错误。如果没有错误，则为 null。 |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | 获取或设置可以附加到对象的一组 16 个键值对。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | 获取或设置对象类型，始终为 thread.run.step。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | 获取或设置此运行步骤所属的运行的 ID。 |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | 获取或设置运行步骤的类型，可以是 message_creation 或 tool_calls。 |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | 获取或设置运行步骤的状态，可以是 in_progress、cancelled、failed、completed 或 expired。 |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | 获取或设置运行步骤的详细信息。 |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | 获取或设置运行的线程 ID。 |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | 获取或设置与运行步骤相关的使用统计信息。当运行步骤的状态为 in_progress 时，此值将为 null。 |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)