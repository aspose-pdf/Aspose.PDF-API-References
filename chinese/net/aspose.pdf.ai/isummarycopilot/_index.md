---
title: "接口 ISummaryCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.ISummaryCopilot 接口。表示用于使用 AI 模型为文档生成摘要的摘要协作员"
type: docs
weight: 640
url: /zh/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot interface

表示使用 AI 模型为文档生成摘要的摘要副驾驶。

```csharp
public interface ISummaryCopilot : IAICopilot
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | 异步获取摘要。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | 异步获取摘要 PDF 文档。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | 异步获取指定页信息的摘要 PDF 文档。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | 异步将摘要保存为 PDF 文件。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | 异步将摘要保存为指定格式的文件。 |

### 另请参见

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


