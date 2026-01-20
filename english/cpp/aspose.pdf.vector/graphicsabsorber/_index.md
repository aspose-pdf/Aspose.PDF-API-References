---
title: Aspose::Pdf::Vector::GraphicsAbsorber class
linktitle: GraphicsAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::GraphicsAbsorber class. Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via GraphicsAbsorber::Elements collection in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.vector/graphicsabsorber/
---
## GraphicsAbsorber class


Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via [GraphicsAbsorber::Elements](../) collection.

```cpp
class GraphicsAbsorber : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Releases all resources used by the [GraphicsAbsorber](./) class. |
| [get_Elements](./get_elements/)() const | Gets collection of search occurrences that are presented with [GraphicElement](../graphicelement/) objects. |
| [GraphicsAbsorber](./graphicsabsorber/)() |  |
| [ResumeUpdate](./resumeupdate/)() | Resume update for [Page::Contents](../) and all [XForm::Contents](../) Was made for performance increase, see also 
[OperatorCollection::ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/)


. |
| [SuppressUpdate](./suppressupdate/)() | Suppresses update for [Page::Contents](../) and all [XForm::Contents](../) Was made for performance increase, see also 
[OperatorCollection::SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)


. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) | Performs search on the specified page. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
