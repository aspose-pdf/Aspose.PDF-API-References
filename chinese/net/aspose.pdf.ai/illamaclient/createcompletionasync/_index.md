---
title: ILlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: ILlamaClient 方法。 在 Llama 服务中创建聊天完成请求
type: docs
weight: 10
url: /zh/net/aspose.pdf.ai/illamaclient/createcompletionasync/
---
## ILlamaClient.CreateCompletionAsync 方法

在 Llama 服务中创建聊天完成请求。

```csharp
public Task<LlamaChatCompletionResponse> CreateCompletionAsync(
    LlamaChatCompletionRequest chatCompletionRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chatCompletionRequest | LlamaChatCompletionRequest | 聊天完成请求。 |
| cancellationToken | Nullable`1 | 取消令牌。 |

### 返回值

聊天完成响应。

### 另请参阅

* 类 [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* 类 [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* 接口 [ILlamaClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)