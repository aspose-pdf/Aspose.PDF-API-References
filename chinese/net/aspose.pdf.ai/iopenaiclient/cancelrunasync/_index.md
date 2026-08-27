---
title: "IOpenAIClient.CancelRunAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步取消线程中的现有运行"
type: docs
weight: 10
url: /zh/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync method

异步取消线程中现有的 run。

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含要取消的运行的线程 ID。 |
| runId | String | 要取消的运行 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行取消的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


