---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步检索助手列表
type: docs
weight: 200
url: /zh/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync 方法

异步检索助手列表。

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | 可选查询参数，用于过滤助手列表。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含助手列表。

### 另请参阅

* 类 [AssistantListResponse](../../assistantlistresponse/)
* 类 [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)