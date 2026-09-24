---
title: "TextPlaceOperator Class"
linktitle: "TextPlaceOperator"
articleTitle: "TextPlaceOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.TextPlaceOperator class. Abstract base class for operators which changes text position (Tm, Td, etc)."
type: docs
weight: 830
url: "/net/aspose.pdf.operators/textplaceoperator/"
keywords: "TextPlaceOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextPlaceOperator class

Abstract base class for operators which changes text position (Tm, Td, etc).

```csharp
public class TextPlaceOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextPlaceOperator](./textplaceoperator/#constructor) | Initializes TextPlaceOperator. |
| [TextPlaceOperator](./textplaceoperator/#constructor_1)(*[TextProperties](../../aspose.pdf.facades/textproperties/)*) | Initializes TextPlaceOperator which accepts TextProperties. |

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

