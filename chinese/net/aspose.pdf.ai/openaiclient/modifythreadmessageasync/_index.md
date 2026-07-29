---
title: "OpenAIClient.ModifyThreadMessageAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。以异步方式修改线程中的现有消息"
type: docs
weight: 430
url: /zh/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync method

异步修改线程中现有的消息。

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含要修改消息的线程的 ID。 |
| threadMessageId | String | 要修改的消息的 ID。 |
| threadMessageModifyRequest | ThreadMessageModifyRequest | 用于修改消息的请求详细信息。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

一个表示异步操作的任务。任务结果包含消息修改后的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当线程消息 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


