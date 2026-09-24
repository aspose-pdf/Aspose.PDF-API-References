---
title: "SetRGBColor Class"
linktitle: "SetRGBColor"
articleTitle: "SetRGBColor"
second_title: "Aspose.PDF for .NET"
description: "Class representing rg operator (set RGB color for non-stroking operators)."
type: docs
weight: 710
url: "/net/aspose.pdf.operators/setrgbcolor/"
keywords: "SetRGBColor, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetRGBColor class

Class representing rg operator (set RGB color for non-stroking operators).

```csharp
public class SetRGBColor : SetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetRGBColor](./setrgbcolor/#constructor)(*[Color](../../aspose.pdf/color/)*) | Initializes operator with color. |
| [SetRGBColor](./setrgbcolor/#constructor_1)(*double, double, double*) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [B](./b/) { get; set; } | Gets or sets the blue component. |
| [G](./g/) { get; set; } | Gets or sets the green component. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [R](./r/) { get; set; } | Gets or sets the red component. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](./tostring/) | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |
| [getColor](./getcolor/) | Returns color specified by operator. |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

