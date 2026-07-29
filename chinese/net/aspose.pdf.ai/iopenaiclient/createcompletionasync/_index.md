---
title: "IOpenAIClient.CreateCompletionAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步创建新的补全"
type: docs
weight: 40
url: /zh/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync method

异步创建新的补全。

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | 包含创建补全详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含补全创建的响应。

### 另请参见

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


