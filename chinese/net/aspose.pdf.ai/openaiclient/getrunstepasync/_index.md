---
title: "OpenAIClient.GetRunStepAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索运行中某个特定步骤的详细信息"
type: docs
weight: 280
url: /zh/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## OpenAIClient.GetRunStepAsync method

异步检索运行中特定步骤的详细信息。

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该运行的线程的 ID。 |
| runId | String | 包含该步骤的运行的 ID。 |
| runStepId | String | 要检索的运行步骤的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行步骤的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行步骤 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


