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
| [TextShowOperator](./textshowoperator/#constructor)() | Initializes TextShowOperator. |
| [TextShowOperator](./textshowoperator/#constructor_1)(TextProperties) | Initializes TextShowOperator which allows to pass TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| virtual [Text](./text/) { get; set; } | Gets text which operator out on the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

