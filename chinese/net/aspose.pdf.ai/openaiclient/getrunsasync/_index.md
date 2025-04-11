---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步检索指定线程的运行列表
type: docs
weight: 260
url: /zh/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync 方法

异步检索指定线程的运行列表。

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 要从中检索运行的线程 ID。 |
| queryParameters | RunListQueryParameters | 可选查询参数，用于过滤运行列表。 |
| cancellationToken | Nullable`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [RunListResponse](../../runlistresponse/)
* 类 [RunListQueryParameters](../../runlistqueryparameters/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)