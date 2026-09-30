---
title: "ConcatenateMatrix Class"
linktitle: "ConcatenateMatrix"
articleTitle: "ConcatenateMatrix"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.ConcatenateMatrix class. Class representing cm operator (concatenate matrix to current transformation matrix)."
type: docs
weight: 150
url: "/net/aspose.pdf.operators/concatenatematrix/"
keywords: "ConcatenateMatrix, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ConcatenateMatrix class

Class representing cm operator (concatenate matrix to current transformation matrix).

```csharp
public class ConcatenateMatrix : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [ConcatenateMatrix](./concatenatematrix/#constructor)(Matrix) | Initializes operator by matrix. |
| [ConcatenateMatrix](./concatenatematrix/#constructor_1)(double, double, double, double, double, double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [Matrix](./matrix/) { get; set; } | Matrix argument of the operator. |

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

