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
product_version: "26.9"
---
## SetAdvancedColor class

Class representing scn operator (set color for non-stroking operations).

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | Initializes operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double, string) | Constructor for scn operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double) | Constructor for scn operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | Constructor for scn operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, double, double, double, string) | Constructor for scn operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(string) | Constructor for scn operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(double[], string) | Constructor for scn operator. |

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
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | Returns color specified by operator. |

### See Also

* class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

