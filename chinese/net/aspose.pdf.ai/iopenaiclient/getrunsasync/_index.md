---
title: "IOpenAIClient.GetRunsAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步检索指定线程的运行列表。"
type: docs
weight: 240
url: /zh/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## IOpenAIClient.GetRunsAsync method

异步检索指定线程的运行列表。

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 要检索运行的线程的 ID。 |
| queryParameters | RunListQueryParameters | 用于过滤运行列表的可选查询参数。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


