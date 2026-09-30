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
public abstract class TableCellElement : TableChildElement, IAdjustPosition, ITextElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. |
| [Alignment](./alignment/) { get; set; } | Gets or sets the cell alignment. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets [`StructureAttributeCollection`](../../aspose.pdf.logicalstructure/structureattributecollection/) object. |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets the cell background color. |
| [Border](./border/) { get; set; } | Gets or sets the cell border. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of [`Element`](../../aspose.pdf.structure/element/) objects. |
| [ColSpan](./colspan/) { get; set; } | Gets or sets the column span. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets [`AttributeOwnerStandard`](../../aspose.pdf.logicalstructure/attributeownerstandard/) object. |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. |
| [IsNoBorder](./isnoborder/) { get; set; } | Gets or sets the cell have border. |
| [IsWordWrapped](./iswordwrapped/) { get; set; } | Gets or sets the cell's text word wrapped. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. |
| [Margin](./margin/) { get; set; } | Gets or sets the padding. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |
| [RowSpan](./rowspan/) { get; set; } | Gets or sets the row span. |
| [StructureTextState](./structuretextstate/) { get; } | Gets [`StructureTextState`](../../aspose.pdf.logicalstructure/structuretextstate/) object for current element. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets the vertical alignment. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append [`Element`](../../aspose.pdf.structure/element/) to collection of children. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Change parent element for current structure element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Clear ID for structure element. |
| [FindElements](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generate ID for structure element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert [`Element`](../../aspose.pdf.structure/element/) to collection of children at specified index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Sets ID for structure element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Sets custom tag for structure element. |
| [SetText](./settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bind a structure element to the content stream BDC operator. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)

