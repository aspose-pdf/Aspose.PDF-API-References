---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步在线程中创建新消息。"
type: docs
weight: 80
url: /zh/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

异步在线程中创建新消息。

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 将创建消息的线程的 ID。 |
| threadMessageRequest | ThreadMessageCreateRequest | 创建消息的请求详细信息。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含消息创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


