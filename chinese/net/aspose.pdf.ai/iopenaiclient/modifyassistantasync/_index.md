---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步修改现有助手
type: docs
weight: 360
url: /zh/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync 方法

异步修改现有助手。

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| assistantId | 字符串 | 要修改的助手的 ID。 |
| assistantModifyRequest | AssistantModifyRequest | 包含修改细节的请求对象。 |
| cancellationToken | 可空`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含助手修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当助手 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [AssistantResponse](../../assistantresponse/)
* 类 [AssistantModifyRequest](../../assistantmodifyrequest/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)