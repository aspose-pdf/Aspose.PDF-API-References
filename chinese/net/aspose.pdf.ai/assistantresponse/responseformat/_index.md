---
title: "AssistantResponse.ResponseFormat"
second_title: "Aspose.PDF for .NET API 参考"
description: "AssistantResponse 属性。获取或设置模型必须输出的格式。兼容 GPT4o、GPT4 Turbo 以及自 gpt3.5turbo1106 起的所有 GPT3.5 Turbo 模型。将其设置为 type json_object 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。使用 JSON 模式时，重要的是必须通过系统或用户消息指示模型自行生成 JSON。否则模型可能会产生无止境的空白流，直至生成达到令牌限制，导致请求长时间运行且似乎卡住。还需注意，如果 finish_reasonlength 表示生成超出 max_tokens 或对话超出最大上下文长度，消息内容可能会被部分截断。"
type: docs
weight: 100
url: /zh/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## AssistantResponse.ResponseFormat property

获取或设置模型必须输出的格式。兼容 GPT-4o、GPT-4 Turbo，以及自 gpt-3.5-turbo-1106 起的所有 GPT-3.5 Turbo 模型。将其设置为 { "type": "json_object" } 可启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：使用 JSON 模式时，您还必须通过系统消息或用户消息指示模型自行生成 JSON。否则，模型可能会产生无限的空白流，直至生成达到 token 限制，导致请求长时间运行且看似"卡住"。另外请注意，如果 finish_reason="length"，消息内容可能会被部分截断，这表明生成超出了 max_tokens 或对话超出了最大上下文长度。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 另请参见

* class [ResponseFormat](../../responseformat/)
* class [AssistantResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


