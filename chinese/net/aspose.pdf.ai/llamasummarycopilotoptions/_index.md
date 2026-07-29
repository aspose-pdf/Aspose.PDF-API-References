---
title: "类 LlamaSummaryCopilotOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.LlamaSummaryCopilotOptions 类。表示用于配置 OpenAICopilot 的选项"
type: docs
weight: 800
url: /zh/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

表示配置 OpenAICopilot 的选项。

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | 获取或设置要处理的文档集合。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。 |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | 获取或设置助手使用的模型。 |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | 获取或设置指示模型提供文档摘要的提示。 |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | 获取或设置包含助手系统指令的文本文件的文件路径。 |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | 获取或设置模型使用的采样温度。 |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | 获取或设置 nucleus 采样的 top-p 值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | 创建 `LlamaSummaryCopilotOptions` 的新实例。 |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | 创建 `LlamaSummaryCopilotOptions` 的实例并使用提供的委托进行配置。 |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | 获取当前的 `LlamaSummaryCopilotOptions`。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 向摘要协作员选项的文档集合中添加 PDF 文档。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | 向摘要协作员选项的文档集合中添加文档路径。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 向摘要协作员选项的文档集合中添加文本文档。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 设置摘要协作员选项的文档集合。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 向摘要协作员选项的文档集合中添加多个 PDF 文档。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 向摘要协作员选项的文档集合中添加多个文档路径。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 向摘要协作员选项的文档集合中添加多个文本文档。 |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | 设置摘要协作员选项的指令。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | 设置摘要协作员选项的最大完成令牌。 |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | 设置摘要协作员选项的模型。 |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | 设置摘要协作员选项的摘要提示。 |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | 设置摘要协作员选项的温度。 |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | 设置摘要协作员选项的 top P 值。 |

### 另请参见

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


