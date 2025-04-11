---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步在指定线程中创建一个运行
type: docs
weight: 50
url: /zh/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync 方法

异步在指定线程中创建一个运行。

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 将要创建运行的线程 ID。 |
| runCreateRequest | RunCreateRequest | 创建运行的请求详细信息。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含运行创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当线程 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [RunResponse](../../runresponse/)
* 类 [RunCreateRequest](../../runcreaterequest/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)