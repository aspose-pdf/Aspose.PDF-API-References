---
title: "TextShowOperator Class"
linktitle: "TextShowOperator"
articleTitle: "TextShowOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.TextShowOperator class. Abstract base class for all operators which used to out text (Tj, TJ, etc)."
type: docs
weight: 840
url: "/net/aspose.pdf.operators/textshowoperator/"
keywords: "TextShowOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextShowOperator class

Abstract base class for all operators which used to out text (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextShowOperator](./textshowoperator/#constructor) | Initializes TextShowOperator. |
| [TextShowOperator](./textshowoperator/#constructor_1)(*[TextProperties](../../aspose.pdf.facades/textproperties/)*) | Initializes TextShowOperator which allows to pass TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [Text](./text/) { get; set; } | Gets text which operator out on the page. |

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

