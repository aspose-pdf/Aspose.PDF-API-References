---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API 参考"
description: "CompletionCreateRequest 属性。获取或设置一个对象，用于控制模型是否调用任何工具。none 表示模型不会调用任何工具，而是生成消息。auto 表示模型可以在生成消息或调用一个或多个工具之间进行选择。required 表示模型必须调用一个或多个工具。通过 type function function name my_function 指定特定工具会强制模型调用该工具。当没有工具时，none 为默认值；如果存在工具，auto 为默认值。"
type: docs
weight: 150
url: /zh/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

获取或设置一个对象，控制模型调用哪个（如果有）工具。none 表示模型不会调用任何工具，而是生成消息。auto 表示模型可以在生成消息或调用一个或多个工具之间选择。required 表示模型必须调用一个或多个工具。通过 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} 指定特定工具会强制模型调用该工具。当没有工具时，默认是 none；如果存在工具，默认是 auto。

```csharp
public ToolChoice ToolChoice { get; set; }
```

### 另请参见

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


