---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.BasicSetColorOperator class. Base class for set color operators
type: docs
weight: 7300
url: /net/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator class

Base class for set color operators.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Gets red component of color |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Gets cyan component of CMYK color. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Gets green component of color |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Gets black component of CMYK color. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Gets magenta component of CMYK color. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Gets red component of color |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Gets yellow component of CMYK color. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepts visitor IOperatorSelector which provides operators processing. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Retirns color specified by the operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


