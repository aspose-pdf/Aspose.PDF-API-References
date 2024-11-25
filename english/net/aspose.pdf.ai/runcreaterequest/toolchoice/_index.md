---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest property. Gets or sets which if any tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like type file_search or type function function name my_function forces the model to call that tool
type: docs
weight: 130
url: /net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice property

Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like {"type": "file_search"} or {"type": "function", "function": {"name": "my_function"}} forces the model to call that tool.

```csharp
public string ToolChoice { get; set; }
```

### See Also

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


