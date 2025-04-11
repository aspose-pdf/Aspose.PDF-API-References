---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步创建一个线程和一个运行
type: docs
weight: 60
url: /zh/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync 方法

异步创建一个线程和一个运行。

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | 创建线程和运行的请求详情。 |
| cancellationToken | Nullable`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程和运行创建的响应。

### 另请参阅

* 类 [RunResponse](../../runresponse/)
* 类 [RunThreadCreateRequest](../../runthreadcreaterequest/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)