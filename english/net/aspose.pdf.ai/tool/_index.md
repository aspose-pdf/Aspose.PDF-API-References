---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Tool class. Represents a tool that can be called by the model
type: docs
weight: 1280
url: /net/aspose.pdf.ai/tool/
---
## Tool class

Represents a tool that can be called by the model.

```csharp
public class Tool
```

## Constructors

| Name | Description |
| --- | --- |
| [Tool](tool/#constructor)() | Initializes a new instance of the `Tool` class. |
| [Tool](tool/#constructor_1)(Function) | Initializes a new instance of the `Tool` class with the specified function. |
| [Tool](tool/#constructor_2)(string) | Initializes a new instance of the `Tool` class with the specified tool type. |

## Properties

| Name | Description |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | Gets a tool instance representing a code interpreter. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | Gets a tool instance representing a file search tool. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | Gets or sets the function that the model can call. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | Gets or sets the type of the tool. Currently, only function is supported. |

## Methods

| Name | Description |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | Creates a new tool instance with the specified function. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


