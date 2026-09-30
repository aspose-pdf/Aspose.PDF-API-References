---
title: "SetColorOperator Class"
linktitle: "SetColorOperator"
articleTitle: "SetColorOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetColorOperator class. Class representing set color operation."
type: docs
weight: 560
url: "/net/aspose.pdf.operators/setcoloroperator/"
keywords: "SetColorOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetColorOperator class

Class representing set color operation.

```csharp
public abstract class SetColorOperator : Operator
```

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepts visitor IOperatorSelector which provides operators processing. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| abstract [getColor](./getcolor/)() | Retirns color specified by the operator. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

