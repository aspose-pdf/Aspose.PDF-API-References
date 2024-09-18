---
title: Aspose::Pdf::LogicalStructure::OBJRElement class
linktitle: OBJRElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::OBJRElement class. Represents object reference entity in logical structure in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf.logicalstructure/objrelement/
---
## OBJRElement class


Represents object reference entity in logical structure.

```cpp
class OBJRElement : public Aspose::Pdf::LogicalStructure::Element
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](../element/appendchild/)(System::SharedPtr\<Element\>) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ClearChilds](../element/clearchilds/)() | Clear all childs. |
| [FindElements](../element/findelements/)(bool) | Find Elements of a given type. |
| [get_ChildElements](../element/get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_ParentElement](../element/get_parentelement/)() const | Get parent element. |
| [InsertChild](../element/insertchild/)(System::SharedPtr\<Element\>, int32_t) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [RemoveChild](../element/removechild/)(int32_t) | Remove child at. |
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
