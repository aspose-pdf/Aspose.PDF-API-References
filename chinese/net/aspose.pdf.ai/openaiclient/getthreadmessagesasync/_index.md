---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步检索特定线程的消息列表
type: docs
weight: 320
url: /zh/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync 方法

异步检索特定线程的消息列表。

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 要检索消息的线程 ID。 |
| queryParameters | ThreadMessageListQueryParameters | 可选查询参数，用于过滤消息列表。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程消息的列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |

### 另见

* 类 [ThreadMessageListResponse](../../threadmessagelistresponse/)
* 类 [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)