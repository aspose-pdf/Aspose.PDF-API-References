---
title: "Element Class"
linktitle: "Element"
articleTitle: "Element"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.Element class. Represents a base class for element in logical structure."
type: docs
weight: 160
url: "/net/aspose.pdf.logicalstructure/element/"
keywords: "Element, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Element class

Represents a base class for element in logical structure.

```csharp
public abstract class Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](./childelements/) { get; } | Gets children collection of [`Element`](../../aspose.pdf.structure/element/) objects. |
| [ParentElement](./parentelement/) { get; } | Get parent element. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](./appendchild/)(Element, bool) | Append [`Element`](../../aspose.pdf.structure/element/) to collection of children. |
| [ClearChilds](./clearchilds/)() | Clear all childs. |
| [FindElements](./findelements/)(bool) | Find Elements of a given type |
| [InsertChild](./insertchild/)(Element, int, bool) | Insert [`Element`](../../aspose.pdf.structure/element/) to collection of children at specified index. |
| [RemoveChild](./removechild/)(int) | Remove child at. |
| abstract [Tag](./tag/)(Annotation) | Bind a structure element to the Annotation. |
| abstract [Tag](./tag/)(Artifact) | Bind a structure element to the Artifact. |
| abstract [Tag](./tag/)(BDC) | Bind a structure element to the content stream BDC operator. |
| abstract [Tag](./tag/)(XForm) | Bind a structure element to the content stream XForm. |
| abstract [Tag](./tag/)(XImage) | Bind a structure element to the XImage. |
| override [ToString](./tostring/)() | Returns a string that represents the current object. |

### See Also

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

