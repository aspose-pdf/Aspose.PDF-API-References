---
title: "TextStateOperator Class"
linktitle: "TextStateOperator"
articleTitle: "TextStateOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.TextStateOperator class. Abstract base class for operators which changes current text state (Tc, Tf, TL, etc)."
type: docs
weight: 850
url: "/net/aspose.pdf.operators/textstateoperator/"
keywords: "TextStateOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextStateOperator class

Abstract base class for operators which changes current text state (Tc, Tf, TL, etc).

```csharp
public class TextStateOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextStateOperator](./textstateoperator/#constructor) | Initializes TextStateOperator. |
| [TextStateOperator](./textstateoperator/#constructor_1)(*[TextProperties](../../aspose.pdf.facades/textproperties/)*) | Initializes TextStateoperator which allows to pass TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf.operators/textoperator/accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. *(Inherited from TextOperator)* |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](../../aspose.pdf/operator/tostring/) | Returns text of operator and its parameters. *(Inherited from Operator)* |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |

### See Also

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

