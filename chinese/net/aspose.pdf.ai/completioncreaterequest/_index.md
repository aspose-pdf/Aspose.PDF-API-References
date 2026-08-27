---
title: "类 CompletionCreateRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.CompletionCreateRequest 类。表示对创建聊天完成端点的请求。"
type: docs
weight: 230
url: /zh/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

表示对创建聊天完成端点的请求。

```csharp
public class CompletionCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | 获取或设置一个介于 -2.0 和 2.0 之间的数值。正值会根据新标记在当前文本中的已有频率进行惩罚，降低模型逐字重复同一行的可能性。 |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 获取或设置指定 token 出现在完成中的可能性。接受一个 JSON 对象，将 token（由分词器中的 token ID 指定）映射到 -100 到 100 之间的偏置值。 |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 获取或设置是否返回输出 token 的对数概率。如果为 true，则返回消息内容中每个输出 token 的对数概率。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | 获取或设置完成时生成的最大 token 数量。 |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | 获取或设置截至目前对话所包含的消息列表。 |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 获取或设置要使用的模型 ID。 |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 获取或设置每条输入消息要生成的聊天完成选项数量。请注意，费用将根据所有选项生成的 token 数量计费。将 n 保持为 1 可降低成本。 |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | 获取或设置一个介于 -2.0 和 2.0 之间的数值。正值会根据新 token 是否已出现在当前文本中进行惩罚，从而增加模型谈论新主题的可能性。 |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | 获取或设置一个对象，指定模型必须输出的格式。兼容 GPT-4 Turbo 和所有高于 gpt-3.5-turbo-1106 的 GPT-3.5 Turbo 模型。将其设置为 { \"type\": \"json_object\" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。 |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | 获取或设置 Seed 值。此功能处于 Beta 阶段。如果指定，系统将尽力进行确定性采样，使得使用相同 seed 和参数的重复请求应返回相同结果。确定性不保证，您应参考 system_fingerprint 响应参数以监控后端的变化。 |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | 获取或设置最多 4 条序列，API 将在这些序列处停止生成后续 token。 |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | 获取或设置是否使用流式传输。如果设置，部分消息增量将被发送，类似于 ChatGPT。Token 将以仅数据的服务器发送事件形式在可用时发送，流将在 data: [DONE] 消息时终止。 |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 获取或设置使用的采样温度，范围在 0 到 2 之间。较高的值（如 0.8）会使输出更随机，而较低的值（如 0.2）会使输出更集中且确定。 |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | 获取或设置一个对象，控制模型调用哪个（如果有）工具。none 表示模型不会调用任何工具，而是生成消息。auto 表示模型可以在生成消息或调用一个或多个工具之间选择。required 表示模型必须调用一个或多个工具。通过 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} 指定特定工具会强制模型调用该工具。当没有工具时，默认是 none；如果存在工具，默认是 auto。 |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | 获取或设置模型可能调用的工具列表。目前，仅支持函数作为工具。使用此项提供模型可能生成 JSON 输入的函数列表。最多支持 128 个函数。 |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 获取或设置温度采样的替代方案，称为 nucleus 采样，模型会考虑 top_p 概率质量的 token 结果。因此 0.1 表示仅考虑占前 10% 概率质量的 token。 |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | 获取或设置代表终端用户的唯一标识符，可帮助 OpenAI 监控和检测滥用行为。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


