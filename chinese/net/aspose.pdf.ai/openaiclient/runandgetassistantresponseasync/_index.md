---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应。"
type: docs
weight: 450
url: /zh/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应。

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | String | 线程的 ID。 |
| runCreateRequest | RunCreateRequest | 运行创建请求。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，返回助手响应字符串。

### 另请参见

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


