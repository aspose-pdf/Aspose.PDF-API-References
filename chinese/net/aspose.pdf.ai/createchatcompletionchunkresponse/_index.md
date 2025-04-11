---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse 类。表示基于提供的输入返回的聊天完成响应的流式块
type: docs
weight: 250
url: /zh/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

表示基于提供的输入返回的聊天完成响应的流式块。

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | 获取或设置聊天完成选择的列表。如果 n 大于 1，则可以包含多个元素。如果您设置了 stream_options: {"include_usage": true}，最后一个块也可以为空。 |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | 获取或设置聊天完成创建时的 Unix 时间戳（以秒为单位）。每个块具有相同的时间戳。 |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | 获取或设置聊天完成的唯一标识符。每个块具有相同的 ID。 |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 获取或设置生成完成的模型。 |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | 获取或设置对象类型，始终为 chat.completion.chunk。 |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | 获取或设置表示模型运行的后端配置的指纹。可以与种子请求参数结合使用，以了解何时进行了可能影响确定性的后端更改。 |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | 获取或设置一个可选字段，仅在您在请求中设置 stream_options: {"include_usage": true} 时存在。当存在时，除了最后一个块外，它包含一个 null 值，最后一个块包含整个请求的令牌使用统计信息。 |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)