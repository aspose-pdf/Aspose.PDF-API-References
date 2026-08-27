---
title: "OpenAIClient.DeleteThreadMessageAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步删除线程中的消息"
type: docs
weight: 160
url: /zh/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync method

异步删除线程中的消息。

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含要删除消息的线程的 ID。 |
| threadMessageId | String | 要删除的消息的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含删除操作的状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当线程消息 Id 为 null 或为空时抛出。 |

### 另请参见

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


