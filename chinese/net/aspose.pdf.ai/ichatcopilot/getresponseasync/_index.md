---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot 方法。异步获取给定消息的响应
type: docs
weight: 20
url: /zh/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

异步获取给定消息的响应。

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 请求响应的输入消息。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，包含响应字符串。

### 另见

* 接口 [IChatCopilot](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

异步获取给定消息列表的响应。

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messages | List`1 | 请求响应的输入消息列表。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，包含响应字符串。

### 另见

* 接口 [IChatCopilot](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)