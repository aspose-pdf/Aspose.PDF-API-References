---
title: Aspose::Pdf::LogicalStructure::TableTRElement class
linktitle: TableTRElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::TableTRElement class. Represents TR structure element in logical structure of the table in C++.'
type: docs
weight: 6700
url: /cpp/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class


Represents TR structure element in logical structure of the table.

```cpp
class TableTRElement : public Aspose::Pdf::LogicalStructure::TableChildElement
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](../element/appendchild/)(System::SharedPtr\<Element\>) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ChangeParentElement](../structureelement/changeparentelement/)(System::SharedPtr\<StructureElement\>) | Change parent element for current structure element. |
| [ClearChilds](../element/clearchilds/)() | Clear all childs. |
| [ClearId](../structureelement/clearid/)() | Clear ID for structure element. |
| [CreateTD](./createtd/)() | Creates [Aspose::Pdf::LogicalStructure::TableTHElement](../tablethelement/) and added it to current table. |
| [CreateTH](./createth/)() | Creates [Aspose::Pdf::LogicalStructure::TableTHElement](../tablethelement/) and added it to current table. |
| [FindElements](../element/findelements/)(bool) | Find Elements of a given type. |
| [GenerateId](../structureelement/generateid/)() | Generate ID for structure element. |
| [get_ActualText](../structureelement/get_actualtext/)() | Gets the actual text for structure element. |
| [get_AlternativeText](../structureelement/get_alternativetext/)() | Gets the alternative text for structure element. |
| [get_Attributes](../structureelement/get_attributes/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) object. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets the row background color. |
| [get_Border](./get_border/)() const | Gets the row border. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_DefaultAttributeOwner](../structureelement/get_defaultattributeowner/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) object. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Gets default cell border. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Gets default margin for row cells. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Gets default text state for row cells. |
| [get_ExpansionText](../structureelement/get_expansiontext/)() | Gets the expansion text for structure element. |
| [get_FixedRowHeight](./get_fixedrowheight/)() const | Gets fixed row height - row may have fixed height. |
| [get_ID](../structureelement/get_id/)() | Gets the ID for structure element. |
| [get_IsInNewPage](./get_isinnewpage/)() const | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [get_IsRowBroken](./get_isrowbroken/)() const | Gets is row can be broken between two pages. |
| [get_Language](../structureelement/get_language/)() | Gets the language for structure element. |
| [get_MinRowHeight](./get_minrowheight/)() const | Gets height for row. |
| [get_Page](../structureelement/get_page/)() | Gets the page on which some or all child elements will be rendered. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [get_StructureType](../structureelement/get_structuretype/)() const | Gets type of structure element. |
| [get_Title](../structureelement/get_title/)() | Gets the title for structure element. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Gets the vertical alignment. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [Remove](../structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
| [set_ActualText](../structureelement/set_actualtext/)(System::String) | Sets the actual text for structure element. |
| [set_AlternativeText](../structureelement/set_alternativetext/)(System::String) | Sets the alternative text for structure element. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets the row background color. |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the row border. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(System::SharedPtr\<BorderInfo\>) | Gets default cell border. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(System::SharedPtr\<MarginInfo\>) | Sets default margin for row cells. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Sets default text state for row cells. |
| [set_ExpansionText](../structureelement/set_expansiontext/)(System::String) | Sets the expansion text for structure element. |
| [set_FixedRowHeight](./set_fixedrowheight/)(double) | Gets fixed row height - row may have fixed height. |
| [set_IsInNewPage](./set_isinnewpage/)(bool) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [set_IsRowBroken](./set_isrowbroken/)(bool) | Gets is row can be broken between two pages. |
| [set_Language](../structureelement/set_language/)(System::String) | Sets the language for structure element. |
| [set_MinRowHeight](./set_minrowheight/)(double) | Gets height for row. |
| [set_Title](../structureelement/set_title/)(System::String) | Sets the title for structure element. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets the vertical alignment. |
| [SetId](../structureelement/setid/)(System::String) | Sets ID for structure element. |
| [SetTag](../structureelement/settag/)(System::String) | Sets custom tag for structure element. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](../structureelement/tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [TableChildElement](../tablechildelement/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
