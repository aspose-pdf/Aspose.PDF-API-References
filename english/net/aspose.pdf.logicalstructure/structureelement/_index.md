---
title: "StructureElement Class"
linktitle: "StructureElement"
articleTitle: "StructureElement"
second_title: "Aspose.PDF for .NET"
description: "Represents a base class for structure elements in logical structure."
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
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](./alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. |
| [Attributes](./attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [DefaultAttributeOwner](./defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](./expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. |
| [ID](./id/) { get; } | Gets the ID for structure element. |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](./language/) { get; set; } | Gets or sets the language for structure element. |
| [Page](./page/) { get; } | Gets the page on which some or all child elements will be rendered. |
| [StructureType](./structuretype/) { get; } | Gets type of structure element. |
| [Title](./title/) { get; set; } | Gets or sets the title for structure element. |

## Methods

| Name | Description |
| --- | --- |
| [ChangeParentElement](./changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. |
| [ClearId](./clearid/) | Clear ID for structure element. |
| [GenerateId](./generateid/) | Generate ID for structure element. |
| [Remove](./remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. |
| [RemoveAndMoveItsChildObjectsToItsParent](./removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. |
| [SetId](./setid/)(*string*) | Sets ID for structure element. |
| [SetTag](./settag/)(*string*) | Sets custom tag for structure element. |
| [Tag](./tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. |
| [Tag](./tag/)(*XForm*) | Bind a structure element to the content stream XForm. |
| [Tag](./tag/)(*XImage*) | Bind a structure element to the XImage. |
| [Tag](./tag/)(*Artifact*) | Bind a structure element to the Artifact. |
| [Tag](./tag/)(*Annotation*) | Bind a structure element to the Annotation. |
| [ToString](./tostring/) | Returns a string that represents the current object. |

### See Also

* class [Element](../../aspose.pdf.structure/element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

