---
title: Class LlamaChatCompletionRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionRequest 类。表示 ChatGPT API 请求的请求体
type: docs
weight: 680
url: /zh/net/aspose.pdf.ai/llamachatcompletionrequest/
---
## LlamaChatCompletionRequest class

表示 ChatGPT API 请求的请求体。

```csharp
public class LlamaChatCompletionRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [LlamaChatCompletionRequest](llamachatcompletionrequest/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/llamachatcompletionrequest/frequencypenalty/) { get; set; } | 设置或获取在采样过程中使用的频率惩罚。 |
| [LogitBias](../../aspose.pdf.ai/llamachatcompletionrequest/logitbias/) { get; set; } | 设置或获取在采样过程中使用的逻辑偏差。 |
| [MaxTokens](../../aspose.pdf.ai/llamachatcompletionrequest/maxtokens/) { get; set; } | 设置或获取在聊天完成中生成的最大令牌数。默认值为 null，表示无限。 |
| [Messages](../../aspose.pdf.ai/llamachatcompletionrequest/messages/) { get; set; } | 设置或获取构成对话的消息列表。 |
| [Model](../../aspose.pdf.ai/llamachatcompletionrequest/model/) { get; set; } | 设置或获取要使用的模型 ID。 |
| [NumberOfChoices](../../aspose.pdf.ai/llamachatcompletionrequest/numberofchoices/) { get; set; } | 设置或获取为每个输入消息生成的聊天完成选择的数量。 |
| [PresencePenalty](../../aspose.pdf.ai/llamachatcompletionrequest/presencepenalty/) { get; set; } | 设置或获取在采样过程中使用的存在惩罚。 |
| [Stream](../../aspose.pdf.ai/llamachatcompletionrequest/stream/) { get; set; } | 设置或获取是否流式传输响应。 |
| [Temperature](../../aspose.pdf.ai/llamachatcompletionrequest/temperature/) { get; set; } | 设置或获取要使用的采样温度，范围在 0 到 2 之间。较高的值如 0.8 会使输出更随机，而较低的值如 0.2 会使其更集中和确定。默认值为 1。 |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)