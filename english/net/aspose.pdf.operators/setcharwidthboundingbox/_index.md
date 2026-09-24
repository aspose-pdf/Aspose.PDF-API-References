---
title: "SetCharWidthBoundingBox Class"
linktitle: "SetCharWidthBoundingBox"
articleTitle: "SetCharWidthBoundingBox"
second_title: "Aspose.PDF for .NET"
description: "Class representing d1 operator (set glyph and bounding box)."
type: docs
weight: 530
url: "/net/aspose.pdf.operators/setcharwidthboundingbox/"
keywords: "SetCharWidthBoundingBox, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetCharWidthBoundingBox class

Class representing d1 operator (set glyph and bounding box).

```csharp
public class SetCharWidthBoundingBox : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetCharWidthBoundingBox](./setcharwidthboundingbox/#constructor)(*double, double, double, double, double, double*) | Initializes SetCharWidthBoundingBox operator. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. *(Inherited from Operator)* |
| [Llx](./llx/) { get; } | Lower-left horizontal coordinate of bounding rectangle. |
| [Lly](./lly/) { get; } | Lower-left vertical coordinate of bounding rectangle. |
| [Urx](./urx/) { get; } | Upper-right horizontal coordinate of bounding rectangle. |
| [Ury](./ury/) { get; } | Upper-right vertical coordinate of bounding rectangle. |
| [Wx](./wx/) { get; } | Horizontal displacement of glyph. |
| [Wy](./wy/) { get; } | Vertical displacement of glyph. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts visitor object to process operator. |
| [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(*Operator*) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc). *(Inherited from Operator)* |
| [ToString](./tostring/) | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(*Operator*) | Compares this instance with the given object. *(Inherited from Operator)* |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

