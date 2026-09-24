---
title: "SetAdvancedColor Class"
linktitle: "SetAdvancedColor"
articleTitle: "SetAdvancedColor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetAdvancedColor class. Class representing scn operator (set color for non-stroking operations)."
type: docs
weight: 480
url: "/net/aspose.pdf.operators/setadvancedcolor/"
keywords: "SetAdvancedColor, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetAdvancedColor class

Class representing scn operator (set color for non-stroking operations).

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetAdvancedColor](./setadvancedcolor/#constructor) | Initializes operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_1)(*double*) | Constructor for scn operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_2)(*string*) | Constructor for scn operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_3)(*double, string*) | Constructor for scn operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_4)(*double[], string*) | Constructor for scn operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_5)(*double, double, double, string*) | Constructor for scn operator. |
| [SetAdvancedColor](./setadvancedcolor/#constructor_6)(*double, double, double, double, string*) | Constructor for scn operator. |

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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Gets Pattern Name. *(Inherited from BasicSetColorAndPatternOperator)* |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Gets red component of color. *(Inherited from BasicSetColorOperator)* |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Gets yellow component of CMYK color. *(Inherited from BasicSetColorOperator)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](../../aspose.pdf/operator/tostring/) | Returns text of operator and its parameters. *(Inherited from Operator)* |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |
| [getColor](./getcolor/) | Returns color specified by operator. |

## Fields

| Name | Description |
| --- | --- |
| [_patternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/_patternname/) | Pattern name. *(Inherited from BasicSetColorAndPatternOperator)* |

### See Also

* class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

