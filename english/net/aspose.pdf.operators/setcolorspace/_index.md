---
title: "SetColorSpace Class"
linktitle: "SetColorSpace"
articleTitle: "SetColorSpace"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetColorSpace class. Class representing cs operator (set colorspace for non-stroking operations)"
type: docs
weight: 580
url: "/net/aspose.pdf.operators/setcolorspace/"
keywords: "SetColorSpace, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetColorSpace class

Class representing cs operator (set colorspace for non-stroking operations)

```csharp
public class SetColorSpace : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColorSpace](./setcolorspace/)(string) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [Name](./name/) { get; set; } | Gets or sets color space name. |

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

