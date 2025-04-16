---
title: RunResponse.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunResponse 属性。获取或设置模型调用的工具（如果有的话）。none 表示模型不会调用任何工具，而是生成一条消息。auto 是默认值，表示模型可以选择生成一条消息或调用一个或多个工具。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，如 强制模型调用该工具。
type: docs
weight: 230
url: /zh/net/aspose.pdf.ai/runresponse/toolchoice/
---
## RunResponse.ToolChoice 属性

获取或设置模型调用的工具（如果有的话）。none 表示模型不会调用任何工具，而是生成一条消息。auto 是默认值，表示模型可以选择生成一条消息或调用一个或多个工具。required 表示模型必须在响应用户之前调用一个或多个工具。指定特定工具，如 {"type": "file_search"} 或 {"type": "function", "function": {"name": "my_function"}} 强制模型调用该工具。

```csharp
public string ToolChoice { get; set; }
```

### 另请参阅

* 类 [RunResponse](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)