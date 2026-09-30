---
title: "SetCMYKColorStroke Class"
linktitle: "SetCMYKColorStroke"
articleTitle: "SetCMYKColorStroke"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetCMYKColorStroke class. Class representing K operator (set CMYK color for stroking operations)."
type: docs
weight: 510
url: "/net/aspose.pdf.operators/setcmykcolorstroke/"
keywords: "SetCMYKColorStroke, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetCMYKColorStroke class

Class representing K operator (set CMYK color for stroking operations).

```csharp
public class SetCMYKColorStroke : SetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetCMYKColorStroke](./setcmykcolorstroke/)(double, double, double, double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [C](./c/) { get; set; } | Gets or sets the cyan component. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](./k/) { get; set; } | Gets or sets the black component. |
| [M](./m/) { get; set; } | Gets or sets the magenta component. |
| [Y](./y/) { get; set; } | Gets or sets the yellow component. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](./getcolor/)() | Returns the RGB color |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

