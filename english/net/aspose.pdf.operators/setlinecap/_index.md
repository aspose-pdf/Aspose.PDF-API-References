---
title: "SetLineCap Class"
linktitle: "SetLineCap"
articleTitle: "SetLineCap"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetLineCap class. Class representing J operator (set line cap style)."
type: docs
weight: 670
url: "/net/aspose.pdf.operators/setlinecap/"
keywords: "SetLineCap, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetLineCap class

Class representing J operator (set line cap style).

```csharp
public class SetLineCap : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetLineCap](./setlinecap/)(LineCap) | Initializes SetLineCap operator |

## Properties

| Name | Description |
| --- | --- |
| [Cap](./cap/) { get; set; } | Gets or sets line caps style. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

