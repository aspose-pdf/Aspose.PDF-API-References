---
title: "SetGrayStroke Class"
linktitle: "SetGrayStroke"
articleTitle: "SetGrayStroke"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetGrayStroke class. Class representing gray level for stroking operations."
type: docs
weight: 650
url: "/net/aspose.pdf.operators/setgraystroke/"
keywords: "SetGrayStroke, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetGrayStroke class

Class representing gray level for stroking operations.

```csharp
public class SetGrayStroke : SetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetGrayStroke](./setgraystroke/)(double) | Initializes operator with the specified color. |

## Properties

| Name | Description |
| --- | --- |
| [Gray](./gray/) { get; set; } | Gets or sets the level of gray value. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| override [getColor](./getcolor/)() | Returns color specified by operator. |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

