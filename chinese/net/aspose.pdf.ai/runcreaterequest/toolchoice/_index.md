---
title: "RunCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API 参考"
description: "RunCreateRequest 属性。获取或设置模型是否调用任何工具。none 表示模型不会调用任何工具，而是生成消息。auto 为默认值，表示模型可以在生成消息或调用一个或多个工具之间选择。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，如 type file_search 或 type function，函数名 my_function，会强制模型调用该工具"
type: docs
weight: 130
url: /zh/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice property

获取或设置模型调用的工具（如果有）。none 表示模型不会调用任何工具，而是生成消息。auto 为默认值，表示模型可以在生成消息或调用一个或多个工具之间进行选择。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，例如 {\"type\": \"file_search\"} 或 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}，会强制模型调用该工具。

```csharp
public string ToolChoice { get; set; }
```

### 另请参见

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


