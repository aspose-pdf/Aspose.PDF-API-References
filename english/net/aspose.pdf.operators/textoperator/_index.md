---
title: "TextOperator Class"
linktitle: "TextOperator"
articleTitle: "TextOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.TextOperator class. Abstract base class for text-related operators (TJ, Tj, Tm, BT, ET, etc)."
type: docs
weight: 820
url: "/net/aspose.pdf.operators/textoperator/"
keywords: "TextOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## TextOperator class

Abstract base class for text-related operators (TJ, Tj, Tm, [BT](../bt/), [ET](../et/), etc).

```csharp
public abstract class TextOperator : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextOperator](textoperator/#constructor)() | Initializes operator. |
| [TextOperator](textoperator/#constructor_1)(TextProperties) | Text operator which accepts text properties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

