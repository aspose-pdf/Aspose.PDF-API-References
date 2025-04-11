---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应
type: docs
weight: 440
url: /zh/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync 方法

使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应。

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadId | 字符串 | 线程的 ID。 |
| runCreateRequest | RunCreateRequest | 运行创建请求。 |
| cancellationToken | 可空`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，包含助手响应字符串。

### 另请参阅

* 类 [RunCreateRequest](../../runcreaterequest/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)