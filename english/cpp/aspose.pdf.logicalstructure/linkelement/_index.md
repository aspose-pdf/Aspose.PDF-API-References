---
title: Aspose::Pdf::LogicalStructure::LinkElement class
linktitle: LinkElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::LinkElement class. Represents Link structure element in logical structure in C++.'
type: docs
weight: 2800
url: /cpp/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class


Represents Link structure element in logical structure.

```cpp
class LinkElement : public Aspose::Pdf::LogicalStructure::AnnotationElement,
                    public Aspose::Pdf::LogicalStructure::ITextElement
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
| [get_AlternateDescriptions](../annotationelement/get_alternatedescriptions/)() const | Gets or Sets the Alternate Descriptions for annotation. [Text](../../aspose.pdf.text/) that shall be displayed for the annotation or, if this type of annotation does not display text, an alternate description of the annotation's contents in human-readable form. |
| [get_AlternativeText](../structureelement/get_alternativetext/)() | Gets the alternative text for structure element. |
| [get_Attributes](../structureelement/get_attributes/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) object. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_DefaultAttributeOwner](../structureelement/get_defaultattributeowner/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) object. |
| [get_ExpansionText](../structureelement/get_expansiontext/)() | Gets the expansion text for structure element. |
| [get_Hyperlink](./get_hyperlink/)() const | Gets or Sets [Hyperlink](../../aspose.pdf/hyperlink/) for Link [Element](../element/). |
| [get_ID](../structureelement/get_id/)() | Gets the ID for structure element. |
| [get_Language](../structureelement/get_language/)() | Gets the language for structure element. |
| [get_Page](../structureelement/get_page/)() | Gets the page on which some or all child elements will be rendered. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [get_StructureTextState](./get_structuretextstate/)() override | Gets [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) object for current element. |
| [get_StructureType](../structureelement/get_structuretype/)() const | Gets type of structure element. |
| [get_Title](../structureelement/get_title/)() | Gets the title for structure element. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [Remove](../structureelement/remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
| [set_ActualText](../structureelement/set_actualtext/)(System::String) | Sets the actual text for structure element. |
| [set_AlternateDescriptions](../annotationelement/set_alternatedescriptions/)(System::String) | Gets or Sets the Alternate Descriptions for annotation. [Text](../../aspose.pdf.text/) that shall be displayed for the annotation or, if this type of annotation does not display text, an alternate description of the annotation's contents in human-readable form. |
| [set_AlternativeText](../structureelement/set_alternativetext/)(System::String) | Sets the alternative text for structure element. |
| [set_ExpansionText](../structureelement/set_expansiontext/)(System::String) | Sets the expansion text for structure element. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Gets or Sets [Hyperlink](../../aspose.pdf/hyperlink/) for Link [Element](../element/). |
| [set_Language](../structureelement/set_language/)(System::String) | Sets the language for structure element. |
| [set_Title](../structureelement/set_title/)(System::String) | Sets the title for structure element. |
| [SetId](../structureelement/setid/)(System::String) | Sets ID for structure element. |
| [SetTag](../structureelement/settag/)(System::String) | Sets custom tag for structure element. |
| [SetText](./settext/)(System::String) override | Appends text content to current text element. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](../structureelement/tag/)(System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](../structureelement/tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [AnnotationElement](../annotationelement/)
* Class [ITextElement](../itextelement/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
