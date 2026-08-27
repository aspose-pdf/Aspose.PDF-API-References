---
title: "IOpenAIClient.CreateAssistantAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步创建新的助手"
type: docs
weight: 30
url: /zh/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## IOpenAIClient.CreateAssistantAsync method

异步创建新的助手。

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

### 另请参见

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantCreateRequest](../../assistantcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


