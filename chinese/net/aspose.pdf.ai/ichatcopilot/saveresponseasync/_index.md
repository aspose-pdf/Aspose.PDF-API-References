---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot 方法。异步将给定消息的响应保存到 PDF 文件
type: docs
weight: 40
url: /zh/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

异步将给定消息的响应保存到 PDF 文件。

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要保存响应的输入消息。 |
| outputFileName | String | 要保存响应的输出 PDF 文件的名称。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参见

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

异步将给定消息的响应保存到指定格式的文件。

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 要保存响应的输入消息。 |
| outputFileName | String | 要保存响应的输出文件的名称。 |
| saveFormat | SaveFormat | 保存响应的格式（如果未指定，则为 PDF）。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参见

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

异步将给定消息列表的响应保存到 PDF 文件。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messages | List`1 | 要保存响应的输入消息列表。 |
| outputFileName | String | 要保存响应的输出 PDF 文件的名称。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参见

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

异步将给定消息列表的响应保存到指定格式的文件。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messages | List`1 | 要保存响应的输入消息列表。 |
| outputFileName | String | 要保存响应的输出文件的名称。 |
| saveFormat | SaveFormat | 保存响应的格式（如果未指定，则为 PDF）。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参见

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)