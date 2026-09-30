---
title: "MCRElement Class"
linktitle: "MCRElement"
articleTitle: "MCRElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.MCRElement class. Represents marked-content reference object in logical structure."
type: docs
weight: 350
url: "/net/aspose.pdf.logicalstructure/mcrelement/"
keywords: "MCRElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MCRElement class

Represents marked-content reference object in logical structure.

```csharp
public sealed class MCRElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of [`Element`](../../aspose.pdf.structure/element/) objects. |
| [MCID](./mcid/) { get; } | Gets MCID of marked-content reference object. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append [`Element`](../../aspose.pdf.structure/element/) to collection of children. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [FindElements](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert [`Element`](../../aspose.pdf.structure/element/) to collection of children at specified index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| override [Tag](./tag/)(Annotation) | Bind a structure element to the Annotation. |
| override [Tag](./tag/)(Artifact) | Bind a structure element to the Artifact. |
| override [Tag](./tag/)(BDC) | Bind a structure element to the content stream BDC operator. |
| override [Tag](./tag/)(XForm) | Bind a structure element to the content stream XForm. |
| override [Tag](./tag/)(XImage) | Bind a structure element to the XImage. |
| override [ToString](./tostring/)() | Returns a string that represents the current object. |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

