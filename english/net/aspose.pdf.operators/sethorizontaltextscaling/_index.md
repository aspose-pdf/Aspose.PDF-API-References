---
title: "SetHorizontalTextScaling Class"
linktitle: "SetHorizontalTextScaling"
articleTitle: "SetHorizontalTextScaling"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetHorizontalTextScaling class. Class representing Tz operator (set horizontal text scaling)."
type: docs
weight: 660
url: "/net/aspose.pdf.operators/sethorizontaltextscaling/"
keywords: "SetHorizontalTextScaling, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetHorizontalTextScaling class

Class representing Tz operator (set horizontal text scaling).

```csharp
public class SetHorizontalTextScaling : TextStateOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetHorizontalTextScaling](./sethorizontaltextscaling/)(double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [HorizontalScaling](./horizontalscaling/) { get; set; } | Gets or sets the horizontal scaling. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextStateOperator](../textstateoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

