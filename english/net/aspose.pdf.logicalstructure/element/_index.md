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
product_version: "26.9"
---
## Element class

Represents a base class for element in logical structure.

```csharp
public abstract class Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of `Element` objects. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append `Element` to collection of children. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert `Element` to collection of children at specified index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(BDC) | Bind a structure element to the content stream BDC operator. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(XForm) | Bind a structure element to the content stream XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(XImage) | Bind a structure element to the XImage. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(Artifact) | Bind a structure element to the Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(Annotation) | Bind a structure element to the Annotation. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Returns a string that represents the current object. |

### See Also

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

