---
title: OpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步创建新的完成
type: docs
weight: 40
url: /zh/net/aspose.pdf.ai/openaiclient/createcompletionasync/
---
## OpenAIClient.CreateCompletionAsync 方法

异步创建新的完成。

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | 包含创建完成详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含来自完成创建的响应。

### 另请参阅

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)