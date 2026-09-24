---
title: "SetColor Class"
linktitle: "SetColor"
articleTitle: "SetColor"
second_title: "Aspose.PDF for .NET"
description: "Represents class for sc operator (set color for non-stroking operations)."
type: docs
weight: 550
url: "/net/aspose.pdf.operators/setcolor/"
keywords: "SetColor, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetColor class

Represents class for sc operator (set color for non-stroking operations).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColor](./setcolor/#constructor) | Initializes operator. |
| [SetColor](./setcolor/#constructor_1)(*double*) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColor](./setcolor/#constructor_2)(*double[]*) | Constructor which allows to specify color components. |
| [SetColor](./setcolor/#constructor_3)(*double, double, double*) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces. |
| [SetColor](./setcolor/#constructor_4)(*double, double, double, double*) | Set color for non-stroking operator for CMYK color space. |

## Properties

| Name | Description |
| --- | --- |
| [B](./b/) { get; set; } | Gets or sets the blue component. |
| [C](./c/) { get; set; } | Gets or sets the cyan component. |
| [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. *(Inherited from BasicSetColorOperator)* |
| [G](./g/) { get; set; } | Gets or sets the green component. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. *(Inherited from BasicSetColorOperator)* |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [K](./k/) { get; set; } | Gets or sets the black component. |
| [M](./m/) { get; set; } | Gets or sets the magenta component. |
| [R](./r/) { get; set; } | Gets or sets the red component. |
| [Y](./y/) { get; set; } | Gets or sets the yellow component. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](./tostring/) | Returns string representation of color. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |
| [getColor](./getcolor/) | Returns color specified by the operator. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

