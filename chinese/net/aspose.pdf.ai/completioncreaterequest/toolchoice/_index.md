---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: CompletionCreateRequest 属性。获取或设置一个对象，该对象控制模型调用哪个工具（如果有的话）。none 意味着模型将不会调用任何工具，而是生成一条消息。auto 意味着模型可以选择生成一条消息或调用一个或多个工具。required 意味着模型必须调用一个或多个工具。通过 {"type": "function", "function": {"name": "my_function"}} 指定特定工具会强制模型调用该工具。当没有工具时，none 是默认值。如果存在工具，auto 是默认值。
type: docs
weight: 150
url: /zh/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice 属性

获取或设置一个对象，该对象控制模型调用哪个（如果有的话）工具。none 意味着模型将不会调用任何工具，而是生成一条消息。auto 意味着模型可以选择生成一条消息或调用一个或多个工具。required 意味着模型必须调用一个或多个工具。通过 {"type": "function", "function": {"name": "my_function"}} 指定特定工具会强制模型调用该工具。当没有工具时，none 是默认值。如果存在工具，auto 是默认值。

```csharp
public ToolChoice ToolChoice { get; set; }
```

### 另请参阅

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)