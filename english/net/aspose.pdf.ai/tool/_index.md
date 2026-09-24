---
title: "Tool Class"
linktitle: "Tool"
articleTitle: "Tool"
second_title: "Aspose.PDF for .NET"
description: "Represents a tool that can be called by the model."
type: docs
weight: 1280
url: "/net/aspose.pdf.ai/tool/"
keywords: "Tool, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Tool class

Represents a tool that can be called by the model.

```csharp
public class Tool
```

## Constructors

| Name | Description |
| --- | --- |
| [Tool](./tool/#constructor) | Initializes a new instance of the [`Tool`](../../aspose.pdf.ai/tool/) class. |
| [Tool](./tool/#constructor_1)(*string*) | Initializes a new instance of the [`Tool`](../../aspose.pdf.ai/tool/) class with the specified tool type. |
| [Tool](./tool/#constructor_2)(*[Function](../../aspose.pdf.ai/function/)*) | Initializes a new instance of the [`Tool`](../../aspose.pdf.ai/tool/) class with the specified function. |

## Properties

| Name | Description |
| --- | --- |
| [CodeInterpreter](./codeinterpreter/) { get; } | Gets a tool instance representing a code interpreter. |
| [FileSearch](./filesearch/) { get; } | Gets a tool instance representing a file search tool. |
| [ToolFunction](./toolfunction/) { get; set; } | Gets or sets the function that the model can call. |
| [ToolType](./tooltype/) { get; set; } | Gets or sets the type of the tool. Currently, only function is supported. |

## Methods

| Name | Description |
| --- | --- |
| [Function](./function/)(*Function*) | Creates a new tool instance with the specified function. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

