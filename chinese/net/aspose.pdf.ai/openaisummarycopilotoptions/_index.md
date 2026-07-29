---
title: "类 OpenAISummaryCopilotOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAISummaryCopilotOptions 类。表示用于配置 OpenAICopilot 的选项"
type: docs
weight: 1010
url: /zh/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions class

表示配置 OpenAICopilot 的选项。

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | 获取或设置助手的名称。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 获取或设置要处理的文档集合。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/maxprompttokens/) { get; set; } | 获取或设置在运行期间可能使用的提示令牌的最大数量。 |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 获取或设置助手使用的模型。 |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | 获取或设置指示模型提供文档摘要的提示。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 获取或设置包含助手系统指令的文本文件的文件路径。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 获取或设置模型使用的采样温度。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 获取或设置 nucleus 采样的 top-p 值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | 创建一个 `OpenAISummaryCopilotOptions` 的新实例。 |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | 创建一个 `OpenAISummaryCopilotOptions` 实例，并使用提供的委托进行配置。 |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | 获取当前的 `OpenAISummaryCopilotOptions`。 |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | 设置摘要协作员选项的助理名称。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 向摘要协作员选项的文档集合中添加 PDF 文档。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | 向摘要协作员选项的文档集合中添加文档路径。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 向摘要协作员选项的文档集合中添加文本文档。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 设置摘要协作员选项的文档集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 向摘要协作员选项的文档集合中添加多个 PDF 文档。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 向摘要协作员选项的文档集合中添加多个文档路径。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 向摘要协作员选项的文档集合中添加多个文本文档。 |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | 设置摘要协作员选项的指令。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | 设置摘要协作员选项的最大完成令牌。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | 设置摘要协作员选项的最大提示令牌。 |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | 设置摘要协作员选项的模型。 |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | 设置摘要协作员选项的摘要提示。 |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | 设置摘要协作员选项的温度。 |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | 设置摘要协作员选项的 top P 值。 |

### 另请参见

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


