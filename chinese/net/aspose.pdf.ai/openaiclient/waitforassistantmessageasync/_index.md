---
title: "OpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步等待线程中助手的第一条消息。"
type: docs
weight: 470
url: /zh/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync method

异步等待线程中来自助手的第一条消息。

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 用于监视第一条助手消息的线程 ID。 |
| queryParameters | ThreadMessageListQueryParameters | 用于过滤消息列表的可选查询参数。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程中的第一条助手消息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


