---
title: LlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: LlamaClient 方法。创建 Llama 服务中的聊天完成请求
type: docs
weight: 10
url: /zh/net/aspose.pdf.ai/llamaclient/createcompletionasync/
---
## LlamaClient.CreateCompletionAsync 方法

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

* class [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* class [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* class [LlamaClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)