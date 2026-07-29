---
title: "IOpenAIClient.CreateThreadAndRunAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步创建线程并在其中运行"
type: docs
weight: 60
url: /zh/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync method

异步创建线程并在其中创建 run。

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | 创建线程和运行的请求详细信息。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程和运行创建的响应。

### 另请参见

* class [RunResponse](../../runresponse/)
* class [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


