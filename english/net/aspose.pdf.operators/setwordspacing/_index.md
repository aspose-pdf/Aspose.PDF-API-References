---
title: "SetWordSpacing Class"
linktitle: "SetWordSpacing"
articleTitle: "SetWordSpacing"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetWordSpacing class. Class representing Tw operator (set word spacing)."
type: docs
weight: 780
url: "/net/aspose.pdf.operators/setwordspacing/"
keywords: "SetWordSpacing, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetWordSpacing class

Class representing Tw operator (set word spacing).

```csharp
public class SetWordSpacing : TextStateOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetWordSpacing](./setwordspacing/)(double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [WordSpacing](./wordspacing/) { get; set; } | Gets or sets the word spacing. |

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

