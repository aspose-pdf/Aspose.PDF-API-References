---
title: "SetDash Class"
linktitle: "SetDash"
articleTitle: "SetDash"
second_title: "Aspose.PDF for .NET"
description: "Class representing d operator (set line dash pattern)."
type: docs
weight: 610
url: "/net/aspose.pdf.operators/setdash/"
keywords: "SetDash, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetDash class

Class representing d operator (set line dash pattern).

```csharp
public class SetDash : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetDash](./setdash/#constructor)(*int[], int*) | Creates set dash pattern operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [Pattern](./pattern/) { get; set; } | Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. |
| [Phase](./phase/) { get; set; } | Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](./tostring/) | Gets operator string representation. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

