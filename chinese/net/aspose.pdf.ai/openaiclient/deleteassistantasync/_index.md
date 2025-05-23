---
title: OpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步删除现有助手
type: docs
weight: 130
url: /zh/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## OpenAIClient.DeleteAssistantAsync 方法

异步删除现有助手。

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| assistantId | 字符串 | 要删除的助手的 ID。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含删除操作的状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当助手 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [DeleteStatusResponse](../../deletestatusresponse/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)