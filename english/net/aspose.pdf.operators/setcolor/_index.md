---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor class. Represents class for sc operator set color for nonstroking operations
type: docs
weight: 5560
url: /net/aspose.pdf.operators/setcolor/
---
## SetColor class

Represents class for sc operator (set color for non-stroking operations).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initializes operator. |
| [SetColor](setcolor/#constructor_1)(double) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColor](setcolor/#constructor_4)(double[]) | Constructor which allows to specify color components. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Set color for non-stroking operator for CMYK color space |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Gets or sets the blue component. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Gets or sets the cyan component. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Gets or sets the green component. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Gets or sets the black component. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Gets or sets the magenta component. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Gets or sets the red component. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Gets or sets the yellow component. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Returns color specified by the operator. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Returns string representation of color. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


