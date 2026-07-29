---
title: "IOpenAIClient.DeleteAssistantAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步删除现有助手。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync method

异步删除现有的助手。

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| assistantId | String | 要删除的助手的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含删除操作的状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当助手 Id 为 null 或为空时抛出。 |

### 另请参见

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


