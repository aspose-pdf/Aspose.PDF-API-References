---
title: "类 OpenAIImageDescriptionCopilotOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions 类。表示用于配置 OpenAICopilot 的选项。"
type: docs
weight: 960
url: /zh/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

表示配置 OpenAICopilot 的选项。

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | 获取或设置助手的名称。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 获取或设置要处理的文档集合。 |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | 获取或设置提示，以指示模型提供图像描述。 |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | 获取或设置用户指定的图像细节级别。"low" 使用更少的令牌，您可以通过 "high" 选择高分辨率。如果未设置，默认值为 "auto"。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/maxprompttokens/) { get; set; } | 获取或设置在运行期间可能使用的提示令牌的最大数量。 |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 获取或设置助手使用的模型。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 获取或设置包含助手系统指令的文本文件的文件路径。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 获取或设置模型使用的采样温度。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 获取或设置 nucleus 采样的 top-p 值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | 创建 `OpenAIImageDescriptionCopilotOptions` 的新实例。 |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 创建 `OpenAIImageDescriptionCopilotOptions` 的实例，并使用提供的委托进行配置。 |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | 获取当前的 `OpenAIImageDescriptionCopilotOptions`。 |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | 设置图像描述协助选项的助手名称。 |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | 向图像描述协助选项的文档集合中添加 PDF 文档。 |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | 向图像描述副驾驶选项的文档集合添加文档路径。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 设置图像描述副驾驶选项的文档集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 向图像描述副驾驶选项的文档集合添加多个 PDF 文档。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | 向图像描述副驾驶选项的文档集合添加多个文档路径。 |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | 设置图像描述副驾驶选项的提示词。 |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | 设置图像细节级别。 |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | 设置图像描述副驾驶选项的说明。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | 设置图像描述副驾驶选项的最大完成标记数。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | 设置图像描述副驾驶选项的最大提示标记数。 |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | 设置图像描述副驾驶选项的模型。 |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | 设置图像描述副驾驶选项的温度。 |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | 设置图像描述副驾驶选项的 top P 值。 |

### 另请参见

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


