---
title: Interface ISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ISummaryCopilot 接口。表示用于使用 AI 模型生成文档摘要的摘要助手
type: docs
weight: 590
url: /zh/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot 接口

表示用于使用 AI 模型生成文档摘要的摘要助手。

```csharp
public interface ISummaryCopilot : IAICopilot
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | 异步获取摘要。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | 异步获取摘要 PDF 文档。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | 异步获取指定页面信息的摘要 PDF 文档。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | 异步将摘要保存到 PDF 文件。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | 异步将摘要保存到指定格式的文件。 |

### 另见

* 接口 [IAICopilot](../iaicopilot/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)