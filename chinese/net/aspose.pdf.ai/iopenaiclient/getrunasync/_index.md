---
title: "IOpenAIClient.GetRunAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步检索线程中具体运行的详细信息"
type: docs
weight: 230
url: /zh/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync method

异步检索线程中特定运行的详细信息。

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该运行的线程的 ID。 |
| runId | String | 要检索的运行的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行的详细信息。

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


