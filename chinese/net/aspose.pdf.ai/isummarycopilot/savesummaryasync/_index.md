---
title: ISummaryCopilot.SaveSummaryAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot 方法。异步将摘要保存到 PDF 文件
type: docs
weight: 30
url: /zh/net/aspose.pdf.ai/isummarycopilot/savesummaryasync/
---
## SaveSummaryAsync(string, CancellationToken?) {#savesummaryasync_1}

异步将摘要保存到 PDF 文件。

```csharp
public Task SaveSummaryAsync(string outputFileName, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | 字符串 | 要保存摘要的输出文件名。 |
| cancellationToken | 可空`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参阅

* 接口 [ISummaryCopilot](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveSummaryAsync(string, SaveFormat, CancellationToken?) {#savesummaryasync}

异步将摘要保存到指定格式的文件中。

```csharp
public Task SaveSummaryAsync(string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | 字符串 | 要保存摘要的输出文件名。 |
| saveFormat | SaveFormat | 保存摘要的格式。 |
| cancellationToken | 可空`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务。

### 另请参阅

* 枚举 [SaveFormat](../../../aspose.pdf/saveformat/)
* 接口 [ISummaryCopilot](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)