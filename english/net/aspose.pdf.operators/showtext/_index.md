---
title: "ShowText Class"
linktitle: "ShowText"
articleTitle: "ShowText"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.ShowText class. Class representing Tj operator (show text)."
type: docs
weight: 800
url: "/net/aspose.pdf.operators/showtext/"
keywords: "ShowText, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ShowText class

Class representing Tj operator (show text).

```csharp
public class ShowText : TextShowOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [ShowText](./showtext/#constructor)() | Initializes Tj operator. |
| [ShowText](./showtext/#constructor_1)(string) | Initializes Tj operator. |
| [ShowText](./showtext/#constructor_2)(int, string) | Initializes Tj opearor. |
| [ShowText](./showtext/#constructor_3)(string, Font) | Initializes Tj opearor. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| override [Text](./text/) { get; set; } | Text of operator. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Produces text code of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextShowOperator](../textshowoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

