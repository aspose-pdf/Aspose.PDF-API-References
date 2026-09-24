---
title: "SetTextMatrix Class"
linktitle: "SetTextMatrix"
articleTitle: "SetTextMatrix"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetTextMatrix class. Class representing Tm operator (set text matrix)."
type: docs
weight: 750
url: "/net/aspose.pdf.operators/settextmatrix/"
keywords: "SetTextMatrix, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetTextMatrix class

Class representing Tm operator (set text matrix).

```csharp
public class SetTextMatrix : TextPlaceOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetTextMatrix](./settextmatrix/#constructor)(*[Matrix](../../aspose.pdf/matrix/)*) | Initializes operator by matrix. |
| [SetTextMatrix](./settextmatrix/#constructor_1)(*double, double, double, double, double, double*) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [Matrix](./matrix/) { get; set; } | Matrix argument of the operator. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](./tostring/) | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |

### See Also

* class [TextPlaceOperator](../textplaceoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

