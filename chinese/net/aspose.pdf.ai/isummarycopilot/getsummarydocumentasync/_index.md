---
title: ISummaryCopilot.GetSummaryDocumentAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot 方法。异步获取摘要 PDF 文档
type: docs
weight: 20
url: /zh/net/aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/
---
## GetSummaryDocumentAsync(CancellationToken?) {#getsummarydocumentasync_1}

异步获取摘要 PDF 文档。

```csharp
public Task<Document> GetSummaryDocumentAsync(CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，包含摘要文档。

### 另请参阅

* class [Document](../../../aspose.pdf/document/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetSummaryDocumentAsync(PageInfo, CancellationToken?) {#getsummarydocumentasync}

异步获取指定页面信息的摘要 PDF 文档。

```csharp
public Task<Document> GetSummaryDocumentAsync(PageInfo pageInfo, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageInfo | PageInfo | 用于生成摘要文档的页面信息。 |
| cancellationToken | Nullable`1 | 取消令牌（可选）。 |

### 返回值

表示异步操作的任务，包含摘要文档。

### 另请参阅

* class [Document](../../../aspose.pdf/document/)
* class [PageInfo](../../../aspose.pdf/pageinfo/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)