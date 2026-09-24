---
title: "BasicSetColorAndPatternOperator Class"
linktitle: "BasicSetColorAndPatternOperator"
articleTitle: "BasicSetColorAndPatternOperator"
second_title: "Aspose.PDF for .NET"
description: "Base operator for all Set Color operators."
type: docs
weight: 70
url: "/net/aspose.pdf.operators/basicsetcolorandpatternoperator/"
keywords: "BasicSetColorAndPatternOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BasicSetColorAndPatternOperator class

Base operator for all Set Color operators.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Gets red component of color. *(Inherited from BasicSetColorOperator)* |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Gets cyan component of CMYK color. *(Inherited from BasicSetColorOperator)* |
| [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. *(Inherited from BasicSetColorOperator)* |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Gets green component of color. *(Inherited from BasicSetColorOperator)* |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. *(Inherited from BasicSetColorOperator)* |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Gets black component of CMYK color. *(Inherited from BasicSetColorOperator)* |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Gets magenta component of CMYK color. *(Inherited from BasicSetColorOperator)* |
| [PatternName](./patternname/) { get; } | Gets Pattern Name. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Gets red component of color. *(Inherited from BasicSetColorOperator)* |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Gets yellow component of CMYK color. *(Inherited from BasicSetColorOperator)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/operator/accept/)(*IOperatorSelector*) | Accepts visitor IOperatorSelector which provides operators processing. *(Inherited from Operator)* |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](../../aspose.pdf/operator/tostring/) | Returns text of operator and its parameters. *(Inherited from Operator)* |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |
| [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/) | Retirns color specified by the operator. *(Inherited from SetColorOperator)* |

## Fields

| Name | Description |
| --- | --- |
| [_patternName](./_patternname/) | Pattern name. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

