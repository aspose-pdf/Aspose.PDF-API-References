---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest 类。表示对创建聊天完成端点的请求
type: docs
weight: 220
url: /zh/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest 类

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
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | 获取或设置一个介于 -2.0 和 2.0 之间的数字。正值根据新令牌在文本中的现有频率对其进行惩罚，从而降低模型逐字重复相同行的可能性。 |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 获取或设置指定令牌在完成中出现的可能性。接受一个 JSON 对象，将令牌（由其在分词器中的令牌 ID 指定）映射到一个关联的偏置值，范围从 -100 到 100。 |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 获取或设置是否返回输出令牌的对数概率。如果为 true，则返回消息内容中每个输出令牌的对数概率。 |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | 获取或设置在完成中生成的最大令牌数。 |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | 获取或设置包含迄今为止对话的消息列表。 |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 获取或设置要使用的模型 ID。 |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 获取或设置为每个输入消息生成的聊天完成选项数量。请注意，您将根据所有选项生成的令牌数量收费。将 n 保持为 1 以最小化成本。 |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | 获取或设置介于 -2.0 和 2.0 之间的数字。正值根据新令牌是否出现在迄今为止的文本中进行惩罚，从而增加模型谈论新主题的可能性。 |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | 获取或设置一个对象，指定模型必须输出的格式。与 GPT-4 Turbo 和所有 GPT-3.5 Turbo 模型（新于 gpt-3.5-turbo-1106）兼容。设置为 { "type": "json_object" } 启用 JSON 模式，确保模型生成的消息是有效的 JSON。 |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | 获取或设置种子值。此功能处于测试阶段。如果指定，我们的系统将尽力进行确定性采样，因此使用相同种子和参数的重复请求应返回相同的结果。不能保证确定性，您应参考 system_fingerprint 响应参数以监控后端的变化。 |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | 获取或设置最多 4 个序列，API 将停止生成进一步的令牌。 |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | 获取或设置是否使用流。如果设置，将发送部分消息增量，类似于 ChatGPT。令牌将作为数据仅服务器发送事件在可用时发送，流将通过数据: [DONE] 消息终止。 |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 获取或设置要使用的采样温度，范围在 0 到 2 之间。较高的值如 0.8 会使输出更随机，而较低的值如 0.2 会使其更集中和确定。 |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | 获取或设置一个对象，控制模型调用哪个（如果有）工具。none 表示模型不会调用任何工具，而是生成一条消息。auto 表示模型可以选择生成消息或调用一个或多个工具。required 表示模型必须调用一个或多个工具。通过 {"type": "function", "function": {"name": "my_function"}} 指定特定工具会强制模型调用该工具。当没有工具时，none 是默认值。当存在工具时，auto 是默认值。 |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | 获取或设置模型可能调用的工具列表。目前，仅支持函数作为工具。使用此功能提供模型可能生成 JSON 输入的函数列表。最多支持 128 个函数。 |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 获取或设置一种替代于使用温度进行采样的方法，称为核采样，其中模型考虑具有 top_p 概率质量的令牌的结果。因此 0.1 意味着仅考虑构成前 10% 概率质量的令牌。 |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | 获取或设置一个唯一标识符，代表您的最终用户，这可以帮助 OpenAI 监控和检测滥用。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)