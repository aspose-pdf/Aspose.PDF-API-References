---
title: "SetRGBColorStroke Class"
linktitle: "SetRGBColorStroke"
articleTitle: "SetRGBColorStroke"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetRGBColorStroke class. Class representing RG operator (set RGB color for stroking operators)."
type: docs
weight: 720
url: "/net/aspose.pdf.operators/setrgbcolorstroke/"
keywords: "SetRGBColorStroke, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetRGBColorStroke class

Class representing RG operator (set RGB color for stroking operators).

```csharp
public class SetRGBColorStroke : SetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetRGBColorStroke](./setrgbcolorstroke/#constructor)(Color) | Initializes operator with color. |
| [SetRGBColorStroke](./setrgbcolorstroke/#constructor_1)(double, double, double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [B](./b/) { get; set; } | Gets or sets the blue component. |
| [G](./g/) { get; set; } | Gets or sets the green component. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [R](./r/) { get; set; } | Gets or sets the red component. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](./getcolor/)() | Returns color specified by operator. |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

