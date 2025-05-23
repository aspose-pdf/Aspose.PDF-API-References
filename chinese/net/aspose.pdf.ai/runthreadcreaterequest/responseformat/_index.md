---
title: RunThreadCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest 属性。获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 以及自 gpt-3.5turbo1106 以来的所有 GPT-3.5 Turbo 模型兼容。将类型设置为 json_object 启用 JSON 模式，这保证了模型生成的消息是有效的 JSON。重要的是：在使用 JSON 模式时，您还必须通过系统或用户消息指示模型自己生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行并且似乎“卡住”。还请注意，如果 finish_reason="length"，则消息内容可能会部分被截断，这表示生成超过了 max_tokens 或对话超过了最大上下文长度。
type: docs
weight: 80
url: /zh/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat 属性

获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 以及自 gpt-3.5-turbo-1106 以来的所有 GPT-3.5 Turbo 模型兼容。将 { "type": "json_object" } 设置为启用 JSON 模式，这保证了模型生成的消息是有效的 JSON。重要：在使用 JSON 模式时，您还必须通过系统或用户消息指示模型自己生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行并且似乎“卡住”。还请注意，如果 finish_reason="length"，则消息内容可能会部分被截断，这表示生成超过了 max_tokens 或对话超过了最大上下文长度。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 另请参阅

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)