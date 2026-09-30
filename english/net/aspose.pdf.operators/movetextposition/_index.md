---
title: "MoveTextPosition Class"
linktitle: "MoveTextPosition"
articleTitle: "MoveTextPosition"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.MoveTextPosition class. Class representing Td operator (move text position)."
type: docs
weight: 400
url: "/net/aspose.pdf.operators/movetextposition/"
keywords: "MoveTextPosition, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MoveTextPosition class

Class representing Td operator (move text position).

```csharp
public class MoveTextPosition : TextPlaceOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [MoveTextPosition](./movetextposition/)(double, double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [X](./x/) { get; set; } | X coordinate of text position. |
| [Y](./y/) { get; set; } | Y coordinate of text position. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextPlaceOperator](../textplaceoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

