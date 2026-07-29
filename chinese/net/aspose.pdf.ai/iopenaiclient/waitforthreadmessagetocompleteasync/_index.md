---
title: "IOpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步等待特定线程消息完成"
type: docs
weight: 450
url: /zh/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync method

异步等待特定线程消息完成。

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该消息的线程的 ID。 |
| threadMessageId | String | 要监视直至完成的消息的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含消息的最终状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当线程消息 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


