---
title: "TableElement Class"
linktitle: "TableElement"
articleTitle: "TableElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.TableElement class. Represents Table structure element in logical structure."
type: docs
weight: 640
url: "/net/aspose.pdf.logicalstructure/tableelement/"
keywords: "TableElement, Aspose.Pdf.LogicalStructure, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TableElement class

Represents Table structure element in logical structure.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. *(Inherited from StructureElement)* |
| [Alignment](./alignment/) { get; set; } | Gets or sets the table alignment. |
| [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) An alternate description of the structure element and its children in. *(Inherited from Element)* |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. *(Inherited from StructureElement)* |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. *(Inherited from StructureElement)* |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets the table background color. |
| [Border](./border/) { get; set; } | Gets or sets the table border. |
| [Broken](./broken/) { get; set; } | Gets or sets table vertial broken;. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gets child elements collection. *(Inherited from Element)* |
| [ColumnAdjustment](./columnadjustment/) { get; set; } | Gets or sets the table column adjustment. |
| [ColumnWidths](./columnwidths/) { get; set; } | Gets the column widths of the table. |
| [CornerStyle](./cornerstyle/) { get; set; } | Gets or sets the styles of the border corners. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. *(Inherited from StructureElement)* |
| [DefaultCellBorder](./defaultcellborder/) { get; set; } | Gets default cell border. |
| [DefaultCellPadding](./defaultcellpadding/) { get; set; } | Gets or sets the default cell padding. |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [DefaultColumnWidth](./defaultcolumnwidth/) { get; set; } | Gets or sets default column width. |
| [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) The expanded form of an abbreviation. *(Inherited from Element)* |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. *(Inherited from StructureElement)* |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. *(Inherited from StructureElement)* |
| [IsBordersIncluded](./isbordersincluded/) { get; set; } | Gets or sets border included in column widhts. |
| [IsBroken](./isbroken/) { get; set; } | Gets or sets the table is broken - will be truncated for next page. |
| [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) A language specifying the natural language for all text. *(Inherited from Element)* |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. *(Inherited from StructureElement)* |
| [Left](./left/) { get; set; } | Gets or sets the table left coordinate. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. *(Inherited from StructureElement)* |
| [RepeatingColumnsCount](./repeatingcolumnscount/) { get; set; } | Gets or sets the maximum columns count for table. |
| [RepeatingRowsCount](./repeatingrowscount/) { get; set; } | Gets the first rows count repeated for several pages. |
| [RepeatingRowsStyle](./repeatingrowsstyle/) { get; set; } | Gets the style for repeating rows. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. *(Inherited from StructureElement)* |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. *(Inherited from StructureElement)* |
| [Top](./top/) { get; set; } | Gets or sets the table top coordinate. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(*PositionSettings*) |  |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(*StructureElement, bool*) | Change parent element for current structure element. *(Inherited from StructureElement)* |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/) | Clear ID for structure element. *(Inherited from StructureElement)* |
| [CreateTBody](./createtbody/) | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/) and added it to current table. |
| [CreateTFoot](./createtfoot/) | Creates [`TableTFootElement`](../../aspose.pdf.logicalstructure/tabletfootelement/) and added it to current table. |
| [CreateTHead](./createthead/) | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/) and added it to current table. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/) | Generate ID for structure element. *(Inherited from StructureElement)* |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(*bool*) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects,. *(Inherited from StructureElement)* |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(*string*) | Sets ID for structure element. *(Inherited from StructureElement)* |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(*string*) | Sets custom tag for structure element. *(Inherited from StructureElement)* |
| [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(*BDC*) | Bind a structure element to the content stream BDC operator. *(Inherited from StructureElement)* |
| [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/) | Returns a string that represents the current object. *(Inherited from StructureElement)* |

### See Also

* class [BLSElement](../blselement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

