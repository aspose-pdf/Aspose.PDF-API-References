---
title: Aspose::Pdf::LogicalStructure::StructureElement class
linktitle: StructureElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::StructureElement class. Represents a base class for structure elements in logical structure in C++.'
type: docs
weight: 5400
url: /cpp/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement class


Represents a base class for structure elements in logical structure.

```cpp
class StructureElement : public Aspose::Pdf::LogicalStructure::Element
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](../element/appendchild/)(System::SharedPtr\<Element\>) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ChangeParentElement](./changeparentelement/)(System::SharedPtr\<StructureElement\>) | Change parent element for current structure element. |
| [ClearChilds](../element/clearchilds/)() | Clear all childs. |
| [ClearId](./clearid/)() | Clear ID for structure element. |
| [FindElements](../element/findelements/)(bool) | Find Elements of a given type. |
| [GenerateId](./generateid/)() | Generate ID for structure element. |
| [get_ActualText](./get_actualtext/)() | Gets the actual text for structure element. |
| [get_AlternativeText](./get_alternativetext/)() | Gets the alternative text for structure element. |
| [get_Attributes](./get_attributes/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) object. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_DefaultAttributeOwner](./get_defaultattributeowner/)() const | Gets [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) object. |
| [get_ExpansionText](./get_expansiontext/)() | Gets the expansion text for structure element. |
| [get_ID](./get_id/)() | Gets the ID for structure element. |
| [get_Language](./get_language/)() | Gets the language for structure element. |
| [get_Page](./get_page/)() | Gets the page on which some or all child elements will be rendered. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [get_StructureType](./get_structuretype/)() const | Gets type of structure element. |
| [get_Title](./get_title/)() | Gets the title for structure element. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [Remove](./remove/)() | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
| [set_ActualText](./set_actualtext/)(System::String) | Sets the actual text for structure element. |
| [set_AlternativeText](./set_alternativetext/)(System::String) | Sets the alternative text for structure element. |
| [set_ExpansionText](./set_expansiontext/)(System::String) | Sets the expansion text for structure element. |
| [set_Language](./set_language/)(System::String) | Sets the language for structure element. |
| [set_Title](./set_title/)(System::String) | Sets the title for structure element. |
| [SetId](./setid/)(System::String) | Sets ID for structure element. |
| [SetTag](./settag/)(System::String) | Sets custom tag for structure element. |
| [Tag](./tag/)(System::SharedPtr\<Aspose::Pdf::Operators::BDC\>) override | Bind a structure element to the content stream BDC operator. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\>) override | Bind a structure element to the Annotation. |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
