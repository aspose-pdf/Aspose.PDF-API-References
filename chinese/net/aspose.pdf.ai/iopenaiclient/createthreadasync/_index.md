---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步创建新线程
type: docs
weight: 70
url: /zh/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## IOpenAIClient.CreateThreadAsync 方法

异步创建新线程。

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | 包含创建线程详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含线程创建的响应。

### 另请参阅

* 类 [ThreadResponse](../../threadresponse/)
* 类 [ThreadCreateRequest](../../threadcreaterequest/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)