---
title: "OpenAIClient.ModifyThreadAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。以异步方式修改现有线程"
type: docs
weight: 420
url: /zh/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## OpenAIClient.ModifyThreadAsync method

异步修改现有线程。

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 要修改的线程的 ID。 |
| threadModifyRequest | ThreadModifyRequest | 包含修改细节的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

一个表示异步操作的任务。任务结果包含线程修改后的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadResponse](../../threadresponse/)
* class [ThreadModifyRequest](../../threadmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


