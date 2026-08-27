---
title: "OpenAIClient.GetThreadAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索特定线程的详细信息"
type: docs
weight: 310
url: /zh/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## OpenAIClient.GetThreadAsync method

异步检索特定线程的详细信息。

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 要检索的线程 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [ThreadResponse](../../threadresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


