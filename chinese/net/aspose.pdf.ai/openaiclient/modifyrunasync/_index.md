---
title: OpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步修改线程中的现有运行
type: docs
weight: 400
url: /zh/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync 方法

异步修改线程中的现有运行。

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 包含运行的线程 ID。 |
| runId | 字符串 | 要修改的运行 ID。 |
| assistantModifyRequest | RunModifyRequest | 修改运行的请求详情。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当运行 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [RunResponse](../../runresponse/)
* 类 [RunModifyRequest](../../runmodifyrequest/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)