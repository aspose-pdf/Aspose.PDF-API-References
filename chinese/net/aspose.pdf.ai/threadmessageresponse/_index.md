---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse class. 表示线程中的一条消息
type: docs
weight: 1160
url: /zh/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

表示线程中的一条消息。

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | 获取或设置（如适用）撰写此消息的助手的 ID。 |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | 获取或设置附加到消息的文件列表。 |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | 获取或设置消息完成时的 Unix 时间戳（以秒为单位）。 |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | 获取或设置消息内容的文本和/或图像数组。 |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | 获取或设置消息创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | 获取或设置标识符，可以在 API 端点中引用。 |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | 获取或设置消息被标记为不完整时的 Unix 时间戳（以秒为单位）。 |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | 获取或设置不完整消息的详细信息，说明消息为何不完整。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | 获取或设置一组 16 个键值对，可以附加到对象上。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | 获取或设置对象类型，始终为 "thread.message"。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | 获取或设置生成消息的实体。可以是 "user" 或 "assistant"。 |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | 获取或设置与创建此消息相关联的运行 ID。当消息是手动创建时，值为 null。 |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | 获取或设置消息的状态。可以是 queued、in_progress、requires_action 或 completed。 |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | 获取或设置此消息所属线程的 ID。 |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)