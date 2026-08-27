---
title: "OpenAIClient.GetThreadMessagesAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索特定线程的消息列表"
type: docs
weight: 330
url: /zh/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync method

异步检索特定线程的消息列表。

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 要检索消息的线程的 ID。 |
| queryParameters | ThreadMessageListQueryParameters | 用于过滤消息列表的可选查询参数。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程消息列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


