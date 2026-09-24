---
title: "TableTDElement Class"
linktitle: "TableTDElement"
articleTitle: "TableTDElement"
second_title: "Aspose.PDF for .NET"
description: "Represents TD structure element in logical structure of the table."
type: docs
weight: 670
url: "/net/aspose.pdf.logicalstructure/tabletdelement/"
keywords: "TableTDElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TableTDElement class

Represents TD structure element in logical structure of the table.

```csharp
public sealed class TableTDElement : TableCellElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. *(Inherited from StructureElement)* |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Gets or sets the cell alignment. *(Inherited from TableCellElement)* |
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. *(Inherited from StructureElement)* |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. *(Inherited from StructureElement)* |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Gets or sets the cell background color. *(Inherited from TableCellElement)* |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Gets or sets the cell border. *(Inherited from TableCellElement)* |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Gets or sets the column span. *(Inherited from TableCellElement)* |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. *(Inherited from StructureElement)* |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. *(Inherited from TableCellElement)* |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. *(Inherited from StructureElement)* |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. *(Inherited from StructureElement)* |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Gets or sets the cell have border. *(Inherited from TableCellElement)* |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Gets or sets the cell's text word wrapped. *(Inherited from TableCellElement)* |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. *(Inherited from StructureElement)* |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Gets or sets the padding. *(Inherited from TableCellElement)* |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. *(Inherited from StructureElement)* |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Gets or sets the row span. *(Inherited from TableCellElement)* |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Gets [`StructureTextState`](../../aspose.pdf.logicalstructure/structuretextstate/) object for current element. *(Inherited from TableCellElement)* |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. *(Inherited from StructureElement)* |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. *(Inherited from StructureElement)* |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Gets or sets the vertical alignment. *(Inherited from TableCellElement)* |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(*PositionSettings*) | *(Inherited from TableCellElement)* |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. *(Inherited from StructureElement)* |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/) | Clear ID for structure element. *(Inherited from StructureElement)* |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/) | Generate ID for structure element. *(Inherited from StructureElement)* |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(*string*) | Sets ID for structure element. *(Inherited from StructureElement)* |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(*string*) | Sets custom tag for structure element. *(Inherited from StructureElement)* |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(*string*) | *(Inherited from TableCellElement)* |
| [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. *(Inherited from StructureElement)* |
| [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/) | Returns a string that represents the current object. *(Inherited from StructureElement)* |

### See Also

* class [TableCellElement](../tablecellelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

