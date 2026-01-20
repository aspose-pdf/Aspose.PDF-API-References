---
title: Aspose::Pdf::LogicalStructure::Element class
linktitle: Element
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::Element class. Represents a base class for element in logical structure in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.logicalstructure/element/
---
## Element class


Represents a base class for element in logical structure.

```cpp
class Element : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](./appendchild/)(System::SharedPtr\<Element\>, bool) | Append [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children. |
| [ClearChilds](./clearchilds/)() | Clear all childs. |
| [FindElements](./findelements/)(bool) | Find Elements of a given type. |
| [get_ChildElements](./get_childelements/)() | Gets children collection of [T:/Aspose::Pdf::LogicalStructure::Element](../) objects. |
| [get_ParentElement](./get_parentelement/)() const | Get parent element. |
| [InsertChild](./insertchild/)(System::SharedPtr\<Element\>, int32_t, bool) | Insert [T:/Aspose::Pdf::LogicalStructure::Element](../) to collection of children at specified index. |
| [RemoveChild](./removechild/)(int32_t) | Remove child at. |
| virtual [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) | Bind a structure element to the content stream BDC operator. |
| virtual [Tag](./tag/)(System::SharedPtr\<XForm\>) | Bind a structure element to the content stream [XForm](../../aspose.pdf/xform/). |
| virtual [Tag](./tag/)(System::SharedPtr\<XImage\>) | Bind a structure element to the [XImage](../../aspose.pdf/ximage/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Artifact\>) | Bind a structure element to the [Artifact](../../aspose.pdf/artifact/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) | Bind a structure element to the Annotation. |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
