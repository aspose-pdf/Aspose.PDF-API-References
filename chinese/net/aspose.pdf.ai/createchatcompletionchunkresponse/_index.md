---
title: "类 CreateChatCompletionChunkResponse"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.CreateChatCompletionChunkResponse 类。表示基于提供的输入，由模型返回的聊天完成响应的流式块。"
type: docs
weight: 260
url: /zh/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

表示模型基于提供的输入返回的聊天完成响应的流式块。

```csharp
public class CreateChatCompletionChunkResponse
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | 获取或设置聊天完成选项的列表。如果 n 大于 1，则可以包含多个元素。如果在请求中设置 stream_options: {"include_usage": true}，最后一个块也可能为空。 |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | 获取或设置聊天完成创建时的 Unix 时间戳（秒）。每个块具有相同的时间戳。 |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | 获取或设置聊天完成的唯一标识符。每个块具有相同的 ID。 |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 获取或设置用于生成完成的模型。 |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | 获取或设置对象类型，该类型始终为 chat.completion.chunk。 |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | 获取或设置表示模型运行的后端配置的指纹。可与 seed 请求参数结合使用，以了解何时进行的后端更改可能影响确定性。 |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | 获取或设置一个可选字段，仅当在请求中设置 stream_options: {"include_usage": true} 时才会出现。出现时，它的值为 null，除最后一个块外，最后一个块包含整个请求的令牌使用统计信息。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


