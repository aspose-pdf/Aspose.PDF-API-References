---
title: "OpenAIClient.GetThreadMessageAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索线程中特定消息的详细信息"
type: docs
weight: 320
url: /zh/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync method

异步检索线程中特定消息的详细信息。

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该消息的线程的 ID。 |
| threadMessageId | String | 要检索的消息的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程消息的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当线程消息 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


