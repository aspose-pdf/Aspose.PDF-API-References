---
title: "BlockTextOperator Class"
linktitle: "BlockTextOperator"
articleTitle: "BlockTextOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.BlockTextOperator class. Abstract base class for text block operators i.e. Begin and End text operators (BT/ET)"
type: docs
weight: 90
url: "/net/aspose.pdf.operators/blocktextoperator/"
keywords: "BlockTextOperator, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BlockTextOperator class

Abstract base class for text block operators i.e. Begin and End text operators ([BT](../bt/)/[ET](../et/))

```csharp
public class BlockTextOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [BlockTextOperator](./blocktextoperator/#constructor)() | Initializes operator. |
| [BlockTextOperator](./blocktextoperator/#constructor_1)(TextProperties) | Initializes BlockTextOperator which accepts TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

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

