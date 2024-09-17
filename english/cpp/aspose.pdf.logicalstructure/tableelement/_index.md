---
title: Aspose::Pdf::LogicalStructure::TableElement class
linktitle: TableElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::TableElement class. Represents Table structure element in logical structure in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class


Represents [Table](../../aspose.pdf/table/) structure element in logical structure.

```cpp
class TableElement : public Aspose::Pdf::LogicalStructure::BLSElement
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](../element/appendchild/)(System::SharedPtr\<Element\>) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ChangeParentElement](../structureelement/changeparentelement/)(System::SharedPtr\<StructureElement\>) | Change parent element for current structure element. |
| [ClearChilds](../element/clearchilds/)() | Clear all childs. |
| [ClearId](../structureelement/clearid/)() | Clear ID for structure element. |
| [CreateTBody](./createtbody/)() | Creates [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) and added it to current table. |
| [CreateTFoot](./createtfoot/)() | Creates [Aspose::Pdf::LogicalStructure::TableTFootElement](../tabletfootelement/) and added it to current table. |
| [CreateTHead](./createthead/)() | Creates [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) and added it to current table. |
| [FindElements](../element/findelements/)(bool) | Find Elements of a given type. |
| [GenerateId](../structureelement/generateid/)() | Generate ID for structure element. |
| [get_ActualText](../structureelement/get_actualtext/)() | Gets the actual text for structure element. |
| [get_Alignment](./get_alignment/)() const | Gets the table alignment. |
| [get_AlternativeText](../structureelement/get_alternativetext/)() | Gets the alternative text for structure element. |
| [get_Attributes](../structureelement/get_attributes/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) object. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets the table background color. |
| [get_Border](./get_border/)() const | Gets the table border. |
| [get_Broken](./get_broken/)() const | Gets table vertial broken;. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Gets the table column adjustment. |
| [get_ColumnWidths](./get_columnwidths/)() const | Gets the column widths of the table. |
| [get_CornerStyle](./get_cornerstyle/)() const | Gets the styles of the border corners. |
| [get_DefaultAttributeOwner](../structureelement/get_defaultattributeowner/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) object. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Gets default cell border. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Gets the default cell padding. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Gets the default cell text state. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Gets default column width. |
| [get_ExpansionText](../structureelement/get_expansiontext/)() | Gets the expansion text for structure element. |
| [get_ID](../structureelement/get_id/)() | Gets the ID for structure element. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Gets border included in column widhts. |
| [get_IsBroken](./get_isbroken/)() const | Gets the table is broken - will be truncated for next page. |
| [get_Language](../structureelement/get_language/)() | Gets the language for structure element. |
| [get_Left](./get_left/)() const | Gets the table left coordinate. |
| [get_Page](../structureelement/get_page/)() | Gets the page on which some or all child elements will be rendered. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Gets the maximum columns count for table. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Gets the first rows count repeated for several pages. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Gets the style for repeating rows. |
| [get_StructureType](../structureelement/get_structuretype/)() const | Gets type of structure element. |
| [get_Title](../structureelement/get_title/)() | Gets the title for structure element. |
| [get_Top](./get_top/)() const | Gets the table top coordinate. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [Remove](../structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
| [set_ActualText](../structureelement/set_actualtext/)(System::String) | Sets the actual text for structure element. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Sets the table alignment. |
| [set_AlternativeText](../structureelement/set_alternativetext/)(System::String) | Sets the alternative text for structure element. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets the table background color. |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the table border. |
| [set_Broken](./set_broken/)(TableBroken) | Sets table vertial broken;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Sets the table column adjustment. |
| [set_ColumnWidths](./set_columnwidths/)(System::String) | Gets the column widths of the table. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Sets the styles of the border corners. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(System::SharedPtr\<BorderInfo\>) | Gets default cell border. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(System::SharedPtr\<MarginInfo\>) | Sets the default cell padding. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Sets the default cell text state. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(System::String) | Sets default column width. |
| [set_ExpansionText](../structureelement/set_expansiontext/)(System::String) | Sets the expansion text for structure element. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Sets border included in column widhts. |
| [set_IsBroken](./set_isbroken/)(bool) | Sets the table is broken - will be truncated for next page. |
| [set_Language](../structureelement/set_language/)(System::String) | Sets the language for structure element. |
| [set_Left](./set_left/)(float) | Sets the table left coordinate. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Sets the maximum columns count for table. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Gets the first rows count repeated for several pages. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Gets the style for repeating rows. |
| [set_Title](../structureelement/set_title/)(System::String) | Sets the title for structure element. |
| [set_Top](./set_top/)(float) | Sets the table top coordinate. |
| [SetId](../structureelement/setid/)(System::String) | Sets ID for structure element. |
| [SetTag](../structureelement/settag/)(System::String) | Sets custom tag for structure element. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](../structureelement/tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [BLSElement](../blselement/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
