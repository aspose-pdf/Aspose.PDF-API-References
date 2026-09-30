---
title: "CurveTo Class"
linktitle: "CurveTo"
articleTitle: "CurveTo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.CurveTo class. Class representing c operator (append curve to path)."
type: docs
weight: 160
url: "/net/aspose.pdf.operators/curveto/"
keywords: "CurveTo, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CurveTo class

Class representing c operator (append curve to path).

```csharp
public class CurveTo : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [CurveTo](./curveto/)(double, double, double, double, double, double) | Initializes curve operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

## Fields

| Name | Description |
| --- | --- |
| [X1](./x1/) | Gets or sets the X1 coordinate. |
| [X2](./x2/) | Gets or sets the X2 coordinate. |
| [X3](./x3/) | Gets or sets the X3 coordinate. |
| [Y1](./y1/) | Gets or sets the Y1 coordinate. |
| [Y2](./y2/) | Gets or sets the Y2 coordinate. |
| [Y3](./y3/) | Gets or sets the Y3 coordinate. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

