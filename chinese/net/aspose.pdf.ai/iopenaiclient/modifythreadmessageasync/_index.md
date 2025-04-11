---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步修改线程中的现有消息
type: docs
weight: 390
url: /zh/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync 方法

异步修改线程中的现有消息。

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 包含要修改的消息的线程 ID。 |
| threadMessageId | 字符串 | 要修改的消息的 ID。 |
| threadMessageModifyRequest | ThreadMessageModifyRequest | 修改消息的请求详细信息。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含消息修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当线程消息 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [ThreadMessageResponse](../../threadmessageresponse/)
* 类 [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)