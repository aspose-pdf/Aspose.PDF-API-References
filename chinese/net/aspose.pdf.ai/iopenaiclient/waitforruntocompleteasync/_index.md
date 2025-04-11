---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步等待线程中的运行完成
type: docs
weight: 440
url: /zh/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## IOpenAIClient.WaitForRunToCompleteAsync 方法

异步等待线程中的运行完成。

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含运行的线程 ID。 |
| runId | String | 监控直到完成的运行 ID。 |
| cancellationToken | Nullable`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行的最终状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [RunResponse](../../runresponse/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)