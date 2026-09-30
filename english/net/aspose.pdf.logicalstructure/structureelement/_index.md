---
title: "StructureElement Class"
linktitle: "StructureElement"
articleTitle: "StructureElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.StructureElement class. Represents a base class for structure elements in logical structure."
type: docs
weight: 550
url: "/net/aspose.pdf.logicalstructure/structureelement/"
keywords: "StructureElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## StructureElement class

Represents a base class for structure elements in logical structure.

```csharp
public abstract class StructureElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](./actualtext/) { get; set; } | Gets or sets the actual text for structure element. |
| [AlternativeText](./alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. |
| [Attributes](./attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of [`Element`](../../aspose.pdf.structure/element/) objects. |
| [DefaultAttributeOwner](./defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. |
| [ExpansionText](./expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. |
| [ID](./id/) { get; } | Gets the ID for structure element. |
| [Language](./language/) { get; set; } | Gets or sets the language for structure element. |
| [Page](./page/) { get; } | Gets the page on which some or all child elements will be rendered. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |
| [StructureType](./structuretype/) { get; } | Gets type of structure element. |
| [Title](./title/) { get; set; } | Gets or sets the title for structure element. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append [`Element`](../../aspose.pdf.structure/element/) to collection of children. |
| [ChangeParentElement](./changeparentelement/)(StructureElement, bool) | Change parent element for current structure element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [ClearId](./clearid/)() | Clear ID for structure element. |
| [FindElements](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [GenerateId](./generateid/)() | Generate ID for structure element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert [`Element`](../../aspose.pdf.structure/element/) to collection of children at specified index. |
| [Remove](./remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveAndMoveItsChildObjectsToItsParent](./removeandmoveitschildobjectstoitsparent/)(bool) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| [SetId](./setid/)(string) | Sets ID for structure element. |
| [SetTag](./settag/)(string) | Sets custom tag for structure element. |
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

