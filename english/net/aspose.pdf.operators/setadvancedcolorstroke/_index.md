---
title: "SetAdvancedColorStroke Class"
linktitle: "SetAdvancedColorStroke"
articleTitle: "SetAdvancedColorStroke"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetAdvancedColorStroke class. Class representing SCN operator (set color for stroking operations)."
type: docs
weight: 490
url: "/net/aspose.pdf.operators/setadvancedcolorstroke/"
keywords: "SetAdvancedColorStroke, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetAdvancedColorStroke class

Class representing SCN operator (set color for stroking operations).

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor)() | Initializes operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor_1)(double) | Constructor for scn operator |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor_2)(double, string) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor_3)(double[], string) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor_4)(double, double, double, string) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/#constructor_5)(double, double, double, double, string) | Constructor for scn operator. |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Gets red component of color |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Gets cyan component of CMYK color. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Gets green component of color |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Gets black component of CMYK color. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Gets magenta component of CMYK color. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Gets Pattern Name. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Gets red component of color |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Gets yellow component of CMYK color. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](./getcolor/)() | Returns color specified by operator. |

### See Also

* class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

