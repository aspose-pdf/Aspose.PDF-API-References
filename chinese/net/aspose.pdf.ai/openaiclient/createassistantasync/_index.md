---
title: OpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步创建一个新的助手
type: docs
weight: 30
url: /zh/net/aspose.pdf.ai/openaiclient/createassistantasync/
---
## OpenAIClient.CreateAssistantAsync 方法

异步创建一个新的助手。

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | 包含创建助手详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含助手创建的响应。

### 另请参阅

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantCreateRequest](../../assistantcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)