---
title: "Aspose::Pdf::LogicalStructure::Element-klass"
linktitle: "Element"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::Element-klass. Representerar en basklass för element i logisk struktur i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.logicalstructure/element/
---
## Element class


Representerar en basklass för element i logisk struktur.

```cpp
class Element : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AppendChild](./appendchild/)(const System::SharedPtr\<Element\>\&, bool) | Lägg till [T:/Aspose::Pdf::LogicalStructure::Element](../) till samling av barn. |
| [ClearChilds](./clearchilds/)() | Rensa alla barn. |
| [FindElements](./findelements/)(bool) | Hitta element av en given typ. |
| [get_ChildElements](./get_childelements/)() | Hämtar barnsamling av [T:/Aspose::Pdf::LogicalStructure::Element](../) objekt. |
| [get_ParentElement](./get_parentelement/)() const | Hämta föräldraelement. |
| [InsertChild](./insertchild/)(const System::SharedPtr\<Element\>\&, int32_t, bool) | Infoga [T:/Aspose::Pdf::LogicalStructure::Element](../) i samling av barn på angivet index. |
| [RemoveChild](./removechild/)(int32_t) | Ta bort barn vid. |
| virtual [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) | Bind ett strukturelement till innehållsströmmen BDC-operator. |
| virtual [Tag](./tag/)(System::SharedPtr\<XForm\>) | Bind ett strukturelement till innehållsströmmen [XForm](../../aspose.pdf/xform/). |
| virtual [Tag](./tag/)(System::SharedPtr\<XImage\>) | Bind ett strukturelement till [XImage](../../aspose.pdf/ximage/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Artifact\>) | Bind ett strukturelement till [Artifact](../../aspose.pdf/artifact/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) | Bind ett strukturelement till Annotation. |
| [ToString](./tostring/)() const override | Returnerar en sträng som representerar det aktuella objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
