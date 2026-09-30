---
title: "MoveTo Class"
linktitle: "MoveTo"
articleTitle: "MoveTo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.MoveTo class. Class representing m operator (move to and begin new subpath)."
type: docs
weight: 420
url: "/net/aspose.pdf.operators/moveto/"
keywords: "MoveTo, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MoveTo class

Class representing m operator (move to and begin new subpath).

```csharp
public class MoveTo : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [MoveTo](./moveto/)(double, double) | Inintalizes new `m` (move to) operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [X](./x/) { get; set; } | X coordinate |
| [Y](./y/) { get; set; } | Y coordinate |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

