---
title: "SetTextLeading Class"
linktitle: "SetTextLeading"
articleTitle: "SetTextLeading"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetTextLeading class. Class represenging TL operator (set text leading)."
type: docs
weight: 740
url: "/net/aspose.pdf.operators/settextleading/"
keywords: "SetTextLeading, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetTextLeading class

Class represenging TL operator (set text leading).

```csharp
public class SetTextLeading : TextStateOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetTextLeading](./settextleading/)(double) | Initializes text leading operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [Leading](./leading/) { get; set; } | Gets or sets the text leading. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Produces text code of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextStateOperator](../textstateoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

