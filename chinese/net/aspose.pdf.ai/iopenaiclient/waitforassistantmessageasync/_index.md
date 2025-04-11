---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步等待线程中助手的第一条消息
type: docs
weight: 430
url: /zh/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync 方法

异步等待线程中助手的第一条消息。

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 要监视的线程的 ID，以获取第一条助手消息。 |
| queryParameters | ThreadMessageListQueryParameters | 可选的查询参数，用于过滤消息列表。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程中的第一条助手消息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [ThreadMessageResponse](../../threadmessageresponse/)
* 类 [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)