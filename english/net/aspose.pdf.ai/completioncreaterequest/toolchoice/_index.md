---
title: "CompletionCreateRequest.ToolChoice"
linktitle: "ToolChoice"
articleTitle: "ToolChoice"
second_title: "Aspose.PDF for .NET API Reference"
description: "CompletionCreateRequest property. Gets or sets an object that controls which (if any) tool is called by the model. none means the model will not call any too..."
type: docs
weight: 170
url: "/net/aspose.pdf.ai/completioncreaterequest/toolchoice/"
product_version: "26.9.0"
---
## CompletionCreateRequest.ToolChoice property

Gets or sets an object that controls which (if any) tool is called by the model.
 none means the model will not call any tool and instead generates a message.
 auto means the model can pick between generating a message or calling one or more tools.
 required means the model must call one or more tools.
 Specifying a particular tool via {"type": "function", "function": {"name": "my_function"}} forces the model to call that tool.
 none is the default when no tools are present.auto is the default if tools are present.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Property Value

[ToolChoice](../../../aspose.pdf.ai/toolchoice/)

### See Also

* class [ToolChoice](../../../aspose.pdf.ai/toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

