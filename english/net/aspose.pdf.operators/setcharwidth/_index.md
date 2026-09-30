---
title: "SetCharWidth Class"
linktitle: "SetCharWidth"
articleTitle: "SetCharWidth"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetCharWidth class. Class representing d0 operator (set glyph width)."
type: docs
weight: 520
url: "/net/aspose.pdf.operators/setcharwidth/"
keywords: "SetCharWidth, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetCharWidth class

Class representing d0 operator (set glyph width).

```csharp
public class SetCharWidth : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetCharWidth](./setcharwidth/)(double, double) | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [Wx](./wx/) { get; } | Horizontal displacement of glyph coordinate. |
| [Wy](./wy/) { get; } | Vertical displacement of glyph coordinate. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

