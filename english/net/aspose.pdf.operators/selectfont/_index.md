---
title: "SelectFont Class"
linktitle: "SelectFont"
articleTitle: "SelectFont"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SelectFont class. Class representing Tf operator (set text font and size)."
type: docs
weight: 470
url: "/net/aspose.pdf.operators/selectfont/"
keywords: "SelectFont, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SelectFont class

Class representing Tf operator (set text font and size).

```csharp
public class SelectFont : TextStateOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SelectFont](./selectfont/)(string, double) | Initializes operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [Name](./name/) { get; } | Name of font. |
| [Size](./size/) { get; } | Size of text. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextStateOperator](../textstateoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

