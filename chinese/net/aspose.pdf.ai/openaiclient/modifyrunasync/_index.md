---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步修改线程中现有的运行。"
type: docs
weight: 410
url: /zh/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync method

异步修改线程中现有的运行。

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 包含该运行的线程的 ID。 |
| runId | String | 要修改的运行的 ID。 |
| assistantModifyRequest | RunModifyRequest | 用于修改运行的请求详细信息。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


