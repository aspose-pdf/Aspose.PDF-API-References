---
title: "IOpenAIClient.CreateRunAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步在指定线程中创建运行。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync method

异步在指定的线程中创建 run。

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 将创建运行的线程 ID。 |
| runCreateRequest | RunCreateRequest | 创建运行的请求详细信息。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 Id 为 null 或为空时抛出。 |

### 另请参见

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


