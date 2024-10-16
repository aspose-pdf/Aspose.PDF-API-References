---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableElement class. Represents Table structure element in logical structure
type: docs
weight: 5190
url: /net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Represents Table structure element in logical structure.

```csharp
public sealed class TableElement : BLSElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Gets or sets the actual text for structure element. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Gets or sets the table alignment. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Gets or sets the alternative text for structure element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Gets StructureAttributeCollection object. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Gets or sets the table background color. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Gets or sets the table border. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Gets or sets table vertial broken; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of Element objects. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Gets or sets the table column adjustment. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Gets the column widths of the table. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Gets or sets the styles of the border corners |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Gets AttributeOwnerStandard object. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Gets default cell border. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Gets or sets the default cell padding. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Gets or sets default column width. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Gets or sets the expansion text for structure element. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Gets the ID for structure element. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Gets or sets border included in column widhts. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Gets or sets the table is broken - will be truncated for next page. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Gets or sets the language for structure element. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Gets or sets the table left coordinate. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Gets the page on which some or all child elements will be rendered. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Gets or sets the maximum columns count for table. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Gets the first rows count repeated for several pages. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Gets the style for repeating rows. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Gets type of structure element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Gets or sets the title for structure element. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Gets or sets the table top coordinate. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element) | Append Element to collection of children. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement) | Change parent element for current structure element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Clear ID for structure element. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Creates [`TableTHeadElement`](../tabletheadelement/) and added it to current table. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Creates [`TableTFootElement`](../tabletfootelement/) and added it to current table. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Creates [`TableTHeadElement`](../tabletheadelement/) and added it to current table. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generate ID for structure element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int) | Insert Element to collection of children at specified index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Sets ID for structure element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Sets custom tag for structure element. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bind a structure element to the Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bind a structure element to the Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bind a structure element to the content stream BDC operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bind a structure element to the content stream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bind a structure element to the XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [BLSElement](../blselement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


