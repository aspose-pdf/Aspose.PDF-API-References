---
title: Aspose::Pdf::LogicalStructure::TableTDElement class
linktitle: TableTDElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::TableTDElement class. Represents TD structure element in logical structure of the table in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf.logicalstructure/tabletdelement/
---
## TableTDElement class


Represents TD structure element in logical structure of the table.

```cpp
class TableTDElement : public Aspose::Pdf::LogicalStructure::TableCellElement
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](../element/appendchild/)(System::SharedPtr\<Element\>) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ChangeParentElement](../structureelement/changeparentelement/)(System::SharedPtr\<StructureElement\>) | Change parent element for current structure element. |
| [ClearChilds](../element/clearchilds/)() | Clear all childs. |
| [ClearId](../structureelement/clearid/)() | Clear ID for structure element. |
| [FindElements](../element/findelements/)(bool) | Find Elements of a given type. |
| [GenerateId](../structureelement/generateid/)() | Generate ID for structure element. |
| [get_ActualText](../structureelement/get_actualtext/)() | Gets the actual text for structure element. |
| [get_Alignment](../tablecellelement/get_alignment/)() const | Gets the cell alignment. |
| [get_AlternativeText](../structureelement/get_alternativetext/)() | Gets the alternative text for structure element. |
| [get_Attributes](../structureelement/get_attributes/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) object. |
| [get_BackgroundColor](../tablecellelement/get_backgroundcolor/)() const | Gets the cell background color. |
| [get_Border](../tablecellelement/get_border/)() const | Gets the cell border. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_ColSpan](../tablecellelement/get_colspan/)() const | Gets the column span. |
| [get_DefaultAttributeOwner](../structureelement/get_defaultattributeowner/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) object. |
| [get_DefaultCellTextState](../tablecellelement/get_defaultcelltextstate/)() | Gets the default cell text state. |
| [get_ExpansionText](../structureelement/get_expansiontext/)() | Gets the expansion text for structure element. |
| [get_ID](../structureelement/get_id/)() | Gets the ID for structure element. |
| [get_IsNoBorder](../tablecellelement/get_isnoborder/)() const | Gets the cell have border. |
| [get_IsWordWrapped](../tablecellelement/get_iswordwrapped/)() const | Gets the cell's text word wrapped. |
| [get_Language](../structureelement/get_language/)() | Gets the language for structure element. |
| [get_Margin](../tablecellelement/get_margin/)() const | Gets the padding. |
| [get_Page](../structureelement/get_page/)() | Gets the page on which some or all child elements will be rendered. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [get_RowSpan](../tablecellelement/get_rowspan/)() const | Gets the row span. |
| [get_StructureTextState](../tablecellelement/get_structuretextstate/)() override | Gets [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) object for current element. |
| [get_StructureType](../structureelement/get_structuretype/)() const | Gets type of structure element. |
| [get_Title](../structureelement/get_title/)() | Gets the title for structure element. |
| [get_VerticalAlignment](../tablecellelement/get_verticalalignment/)() const | Gets the vertical alignment. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [Remove](../structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
| [set_ActualText](../structureelement/set_actualtext/)(System::String) | Sets the actual text for structure element. |
| [set_Alignment](../tablecellelement/set_alignment/)(HorizontalAlignment) | Sets the cell alignment. |
| [set_AlternativeText](../structureelement/set_alternativetext/)(System::String) | Sets the alternative text for structure element. |
| [set_BackgroundColor](../tablecellelement/set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets the cell background color. |
| [set_Border](../tablecellelement/set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the cell border. |
| [set_ColSpan](../tablecellelement/set_colspan/)(int32_t) | Sets the column span. |
| [set_DefaultCellTextState](../tablecellelement/set_defaultcelltextstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Sets the default cell text state. |
| [set_ExpansionText](../structureelement/set_expansiontext/)(System::String) | Sets the expansion text for structure element. |
| [set_IsNoBorder](../tablecellelement/set_isnoborder/)(bool) | Sets the cell have border. |
| [set_IsWordWrapped](../tablecellelement/set_iswordwrapped/)(bool) | Sets the cell's text word wrapped. |
| [set_Language](../structureelement/set_language/)(System::String) | Sets the language for structure element. |
| [set_Margin](../tablecellelement/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets the padding. |
| [set_RowSpan](../tablecellelement/set_rowspan/)(int32_t) | Sets the row span. |
| [set_Title](../structureelement/set_title/)(System::String) | Sets the title for structure element. |
| [set_VerticalAlignment](../tablecellelement/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets the vertical alignment. |
| [SetId](../structureelement/setid/)(System::String) | Sets ID for structure element. |
| [SetTag](../structureelement/settag/)(System::String) | Sets custom tag for structure element. |
| [SetText](../tablecellelement/settext/)(System::String) override | Appends text content to current text element. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](../structureelement/tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [TableCellElement](../tablecellelement/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
