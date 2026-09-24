---
title: "TableCellElement Class"
linktitle: "TableCellElement"
articleTitle: "TableCellElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.TableCellElement class. Represents a base class for table cell elements (TH and TD) in logical structure."
type: docs
weight: 620
url: "/net/aspose.pdf.logicalstructure/tablecellelement/"
keywords: "TableCellElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TableCellElement class

Represents a base class for table cell elements (TH and TD) in logical structure.

```csharp
public abstract class TableCellElement : TableChildElement, ITextElement, IAdjustPosition
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. *(Inherited from StructureElement)* |
| [Alignment](./alignment/) { get; set; } | Gets or sets the cell alignment. |
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. *(Inherited from StructureElement)* |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. *(Inherited from StructureElement)* |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets the cell background color. |
| [Border](./border/) { get; set; } | Gets or sets the cell border. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [ColSpan](./colspan/) { get; set; } | Gets or sets the column span. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. *(Inherited from StructureElement)* |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. *(Inherited from StructureElement)* |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. *(Inherited from StructureElement)* |
| [IsNoBorder](./isnoborder/) { get; set; } | Gets or sets the cell have border. |
| [IsWordWrapped](./iswordwrapped/) { get; set; } | Gets or sets the cell's text word wrapped. |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. *(Inherited from StructureElement)* |
| [Margin](./margin/) { get; set; } | Gets or sets the padding. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. *(Inherited from StructureElement)* |
| [RowSpan](./rowspan/) { get; set; } | Gets or sets the row span. |
| [StructureTextState](./structuretextstate/) { get; } | Gets [`StructureTextState`](../../aspose.pdf.logicalstructure/structuretextstate/) object for current element. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. *(Inherited from StructureElement)* |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. *(Inherited from StructureElement)* |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets the vertical alignment. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(*PositionSettings*) |  |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. *(Inherited from StructureElement)* |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/) | Clear ID for structure element. *(Inherited from StructureElement)* |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/) | Generate ID for structure element. *(Inherited from StructureElement)* |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(*string*) | Sets ID for structure element. *(Inherited from StructureElement)* |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(*string*) | Sets custom tag for structure element. *(Inherited from StructureElement)* |
| [SetText](./settext/)(*string*) |  |
| [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. *(Inherited from StructureElement)* |
| [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/) | Returns a string that represents the current object. *(Inherited from StructureElement)* |

### See Also

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

