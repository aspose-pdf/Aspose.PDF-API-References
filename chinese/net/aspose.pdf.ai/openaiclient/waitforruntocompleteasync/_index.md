---
title: "OpenAIClient.WaitForRunToCompleteAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步地在线程中等待运行完成。"
type: docs
weight: 480
url: /zh/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## OpenAIClient.WaitForRunToCompleteAsync method

异步等待线程中运行完成。

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该运行的线程的 ID。 |
| runId | String | 要监视直至完成的运行的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行的最终状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


