---
title: "BasicSetColorOperator Class"
linktitle: "BasicSetColorOperator"
articleTitle: "BasicSetColorOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.BasicSetColorOperator class. Base class for set color operators."
type: docs
weight: 80
url: "/net/aspose.pdf.operators/basicsetcoloroperator/"
keywords: "BasicSetColorOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BasicSetColorOperator class

Base class for set color operators.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Properties

| Name | Description |
| --- | --- |
| [B](./b/) { get; } | Gets red component of color. |
| [C](./c/) { get; } | Gets cyan component of CMYK color. |
| [Color](./color/) { get; } | Gets array of color components. |
| [G](./g/) { get; } | Gets green component of color. |
| [Gray](./gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [K](./k/) { get; } | Gets black component of CMYK color. |
| [M](./m/) { get; } | Gets magenta component of CMYK color. |
| [R](./r/) { get; } | Gets red component of color. |
| [Y](./y/) { get; } | Gets yellow component of CMYK color. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/operator/accept/)(*IOperatorSelector*) | Accepts visitor IOperatorSelector which provides operators processing. *(Inherited from Operator)* |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](../../aspose.pdf/operator/tostring/) | Returns text of operator and its parameters. *(Inherited from Operator)* |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |
| [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/) | Retirns color specified by the operator. *(Inherited from SetColorOperator)* |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

