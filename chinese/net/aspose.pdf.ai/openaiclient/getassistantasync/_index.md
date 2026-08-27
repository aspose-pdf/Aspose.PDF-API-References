---
title: "OpenAIClient.GetAssistantAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索特定助手的详细信息"
type: docs
weight: 190
url: /zh/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync method

异步检索特定助手的详细信息。

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| assistantId | String | 要检索的助手的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含助手的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当助手 Id 为 null 或为空时抛出。 |

### 另请参见

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


