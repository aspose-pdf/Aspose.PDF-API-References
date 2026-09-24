---
title: "TableTRElement Class"
linktitle: "TableTRElement"
articleTitle: "TableTRElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.TableTRElement class. Represents TR structure element in logical structure of the table."
type: docs
weight: 710
url: "/net/aspose.pdf.logicalstructure/tabletrelement/"
keywords: "TableTRElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TableTRElement class

Represents TR structure element in logical structure of the table.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. *(Inherited from StructureElement)* |
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. *(Inherited from StructureElement)* |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. *(Inherited from StructureElement)* |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets the row background color. |
| [Border](./border/) { get; set; } | Gets or sets the row border. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. *(Inherited from StructureElement)* |
| [DefaultCellBorder](./defaultcellborder/) { get; set; } | Gets default cell border. |
| [DefaultCellPadding](./defaultcellpadding/) { get; set; } | Gets or sets default margin for row cells. |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets default text state for row cells. |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. *(Inherited from StructureElement)* |
| [FixedRowHeight](./fixedrowheight/) { get; set; } | Gets fixed row height - row may have fixed height. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. *(Inherited from StructureElement)* |
| [IsInNewPage](./isinnewpage/) { get; set; } | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [IsRowBroken](./isrowbroken/) { get; set; } | Gets is row can be broken between two pages. |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. *(Inherited from StructureElement)* |
| [MinRowHeight](./minrowheight/) { get; set; } | Gets height for row. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. *(Inherited from StructureElement)* |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. *(Inherited from StructureElement)* |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. *(Inherited from StructureElement)* |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets the vertical alignment. |

## Methods

| Name | Description |
| --- | --- |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. *(Inherited from StructureElement)* |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/) | Clear ID for structure element. *(Inherited from StructureElement)* |
| [CreateTD](./createtd/) | Creates [`TableTHElement`](../../aspose.pdf.logicalstructure/tablethelement/) and added it to current table. |
| [CreateTH](./createth/) | Creates [`TableTHElement`](../../aspose.pdf.logicalstructure/tablethelement/) and added it to current table. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/) | Generate ID for structure element. *(Inherited from StructureElement)* |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(*string*) | Sets ID for structure element. *(Inherited from StructureElement)* |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(*string*) | Sets custom tag for structure element. *(Inherited from StructureElement)* |
| [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. *(Inherited from StructureElement)* |
| [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/) | Returns a string that represents the current object. *(Inherited from StructureElement)* |

### See Also

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

