---
title: "ArtElement Class"
linktitle: "ArtElement"
articleTitle: "ArtElement"
second_title: "Aspose.PDF for .NET"
description: "Represents Art structure element in logical structure."
type: docs
weight: 40
url: "/net/aspose.pdf.logicalstructure/artelement/"
keywords: "ArtElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ArtElement class

Represents Art structure element in logical structure.

```csharp
public sealed class ArtElement : GroupingElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. *(Inherited from StructureElement)* |
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. *(Inherited from StructureElement)* |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. *(Inherited from StructureElement)* |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. *(Inherited from StructureElement)* |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. *(Inherited from StructureElement)* |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. *(Inherited from StructureElement)* |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. *(Inherited from StructureElement)* |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. *(Inherited from StructureElement)* |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. *(Inherited from StructureElement)* |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. *(Inherited from StructureElement)* |

## Methods

| Name | Description |
| --- | --- |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. *(Inherited from StructureElement)* |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/) | Clear ID for structure element. *(Inherited from StructureElement)* |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/) | Generate ID for structure element. *(Inherited from StructureElement)* |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(*string*) | Sets ID for structure element. *(Inherited from StructureElement)* |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(*string*) | Sets custom tag for structure element. *(Inherited from StructureElement)* |
| [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. *(Inherited from StructureElement)* |
| [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/) | Returns a string that represents the current object. *(Inherited from StructureElement)* |

### See Also

* class [GroupingElement](../groupingelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

