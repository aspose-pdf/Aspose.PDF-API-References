---
title: "SetMiterLimit Class"
linktitle: "SetMiterLimit"
articleTitle: "SetMiterLimit"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetMiterLimit class. Class representing M operator (set miter limit)."
type: docs
weight: 700
url: "/net/aspose.pdf.operators/setmiterlimit/"
keywords: "SetMiterLimit, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetMiterLimit class

Class representing M operator (set miter limit).

```csharp
public class SetMiterLimit : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetMiterLimit](./setmiterlimit/)(double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [MiterLimit](./miterlimit/) { get; set; } | Gets or sets the miter limit. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

