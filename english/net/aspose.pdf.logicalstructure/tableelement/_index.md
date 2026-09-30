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
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. |
| [Alignment](./alignment/) { get; set; } | Gets or sets the table alignment. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets the table background color. |
| [Border](./border/) { get; set; } | Gets or sets the table border. |
| [Broken](./broken/) { get; set; } | Gets or sets table vertial broken; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of [`Element`](../../aspose.pdf.structure/element/) objects. |
| [ColumnAdjustment](./columnadjustment/) { get; set; } | Gets or sets the table column adjustment. |
| [ColumnWidths](./columnwidths/) { get; set; } | Gets the column widths of the table. |
| [CornerStyle](./cornerstyle/) { get; set; } | Gets or sets the styles of the border corners |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. |
| [DefaultCellBorder](./defaultcellborder/) { get; set; } | Gets default cell border. |
| [DefaultCellPadding](./defaultcellpadding/) { get; set; } | Gets or sets the default cell padding. |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [DefaultColumnWidth](./defaultcolumnwidth/) { get; set; } | Gets or sets default column width. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. |
| [IsBordersIncluded](./isbordersincluded/) { get; set; } | Gets or sets border included in column widhts. |
| [IsBroken](./isbroken/) { get; set; } | Gets or sets the table is broken - will be truncated for next page. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. |
| [Left](./left/) { get; set; } | Gets or sets the table left coordinate. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |
| [RepeatingColumnsCount](./repeatingcolumnscount/) { get; set; } | Gets or sets the maximum columns count for table. |
| [RepeatingRowsCount](./repeatingrowscount/) { get; set; } | Gets the first rows count repeated for several pages. |
| [RepeatingRowsStyle](./repeatingrowsstyle/) { get; set; } | Gets the style for repeating rows. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. |
| [Top](./top/) { get; set; } | Gets or sets the table top coordinate. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append [`Element`](../../aspose.pdf.structure/element/) to collection of children. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Change parent element for current structure element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Clear ID for structure element. |
| [CreateTBody](./createtbody/)() | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/) and added it to current table. |
| [CreateTFoot](./createtfoot/)() | Creates [`TableTFootElement`](../../aspose.pdf.logicalstructure/tabletfootelement/) and added it to current table. |
| [CreateTHead](./createthead/)() | Creates [`TableTHeadElement`](../../aspose.pdf.logicalstructure/tabletheadelement/) and added it to current table. |
| [FindElements](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generate ID for structure element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert [`Element`](../../aspose.pdf.structure/element/) to collection of children at specified index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Sets ID for structure element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Sets custom tag for structure element. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bind a structure element to the content stream BDC operator. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [BLSElement](../blselement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

