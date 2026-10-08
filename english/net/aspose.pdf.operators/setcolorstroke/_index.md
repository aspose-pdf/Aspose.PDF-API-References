---
title: "SetColorStroke Class"
linktitle: "SetColorStroke"
articleTitle: "SetColorStroke"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetColorStroke class. Class representing SC operator set color for stroking color operators."
type: docs
weight: 600
url: "/net/aspose.pdf.operators/setcolorstroke/"
keywords: "SetColorStroke, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## SetColorStroke class

Class representing SC operator set color for stroking color operators.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initializes operator. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColorStroke](setcolorstroke/#constructor_3)(double[]) | Constructor which allows to set color components. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double, double, double, double) | Set color for stroking operator for CMYK color space |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Gets or sets the blue component. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Gets or sets the cyan component. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Gets or sets the green component. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Gets or sets the black component. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Gets or sets the magenta component. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Gets or sets the red component. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Gets or sets the yellow component. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Returns color specified by operator. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

