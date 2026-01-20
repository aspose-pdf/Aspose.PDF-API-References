---
title: Aspose::Pdf::Vector::XFormPlacement class
linktitle: XFormPlacement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::XFormPlacement class. Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class


Represents [XForm](../../aspose.pdf/xform/) placement. If the [XForm](../../aspose.pdf/xform/) is displayed on the page more than 1 time, all XformPlacements associated with this [XForm](../../aspose.pdf/xform/) will have common graphical elements, but different graphical states.

```cpp
class XFormPlacement : public Aspose::Pdf::Vector::GraphicElement
```

## Methods

| Method | Description |
| --- | --- |
| [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) override | Adds current element on the page. If there are many elements to add better use [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [get_Elements](./get_elements/)() const | Gets graphic elements inside this [XForm](../../aspose.pdf/xform/). |
| [get_Name](./get_name/)() | Gets name of the [XForm](../../aspose.pdf/xform/). |
| [get_Rectangle](./get_rectangle/)() override | Gets the bounding rectangle of the [GraphicElement](../graphicelement/). |
| [get_XForm](./get_xform/)() const | Gets [XForm](../../aspose.pdf/xform/) associated with this [XFormPlacement](./). |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) override | Sets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
## See Also

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
