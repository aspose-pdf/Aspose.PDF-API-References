---
title: "类 OpenAIChatCopilotOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIChatCopilotOptions 类。表示用于配置 OpenAICopilot 的选项"
type: docs
weight: 890
url: /zh/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions class

表示配置 OpenAICopilot 的选项。

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | 获取或设置助手的名称。 |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | 获取或设置上下文备份 JSON 的文件路径。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 获取或设置要处理的文档集合。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 获取或设置在运行期间可能使用的最大完成标记数。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/maxprompttokens/) { get; set; } | 获取或设置在运行期间可能使用的提示令牌的最大数量。 |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 获取或设置助手使用的模型。 |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | 获取或设置指示是否从备份恢复上下文的值。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 获取或设置包含助手系统指令的文本文件的文件路径。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 获取或设置模型使用的采样温度。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 获取或设置 nucleus 采样的 top-p 值。 |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | 获取或设置线程的截断策略。 |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | 获取或设置向量存储过期前的天数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | 创建 `OpenAIChatCopilotOptions` 的新实例。 |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | 创建 `OpenAIChatCopilotOptions` 的实例，并使用提供的委托进行配置。 |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | 获取当前的 `OpenAIChatCopilotOptions`。 |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | 设置聊天副驾驶选项的助理名称。 |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | 在聊天副驾驶选项中设置上下文备份 JSON 的文件路径。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | 向聊天副驾驶选项的 Document 集合中添加 PDF Document。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | 向聊天副驾驶选项的文档集合添加文档路径。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | 向聊天副驾驶选项的文档集合添加文本文档。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 设置聊天副驾驶选项的文档集合。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 向聊天副驾驶选项的文档集合添加多个 PDF 文档。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 向聊天副驾驶选项的文档集合添加多个文档路径。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 向聊天副驾驶选项的文档集合添加多个文本文档。 |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | 设置聊天副驾驶选项的指令。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | 设置聊天副驾驶选项的最大完成 token 数。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | 设置聊天副驾驶选项的最大提示 token 数。 |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | 设置聊天副驾驶选项的模型。 |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | 设置是否在聊天副驾驶选项中从备份恢复上下文。 |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | 设置聊天副驾驶选项的温度。 |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | 设置聊天副驾驶选项的 top P 值。 |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | 设置聊天副驾驶选项的截断策略。 |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | 设置聊天副驾驶选项中向量存储过期的天数。 |

### 另请参见

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


