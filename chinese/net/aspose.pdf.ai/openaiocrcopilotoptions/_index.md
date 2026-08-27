---
title: "类 OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions 类。表示用于配置 OpenAIOcrCopilot 的选项。"
type: docs
weight: 990
url: /zh/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

表示用于配置 OpenAIOcrCopilot 的选项。

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | 获取或设置图像分析的细节级别。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 获取或设置要处理的文档集合。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。 |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 获取或设置助手使用的模型。 |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | 获取或设置用于将 PDF 页面转换为图像的分辨率。默认值为 300 dpi。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 获取或设置包含助手系统指令的文本文件的文件路径。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 获取或设置模型使用的采样温度。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 获取或设置 nucleus 采样的 top-p 值。 |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | 获取或设置用户提示。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | 创建一个新的 `OpenAIOcrCopilotOptions` 实例。 |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | 创建 `OpenAIOcrCopilotOptions` 实例并使用提供的委托进行配置。 |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | 获取当前的 `OpenAIOcrCopilotOptions`。 |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | 设置图像分析的细节级别。 |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | 将 PDF Document 添加到 Document 集合。 |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | 将 Document 路径添加到 Document 集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 设置 Document 集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 将多个 PDF Document 添加到 Document 集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | 将多个 Document 路径添加到 Document 集合。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | 设置最大完成令牌数。 |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | 设置模型。 |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | 设置用于将 PDF 页面转换为图像的分辨率。默认值为 300 dpi。 |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | 设置 OCR 副驾驶选项的指令。 |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | 设置温度。 |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | 设置 top P 值。 |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | 设置用户提示。 |

### 另请参见

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


