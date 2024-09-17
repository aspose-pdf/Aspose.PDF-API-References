---
title: Aspose::Pdf::Vector::XFormPlacement class
linktitle: XFormPlacement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::XFormPlacement class. Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states in C++.'
type: docs
weight: 700
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
| [Dispose](../graphicelement/dispose/)() override | Releases all resources used by the [GraphicElement](../graphicelement/) class. |
| [get_Elements](./get_elements/)() const | Gets graphic elements inside this [XForm](../../aspose.pdf/xform/). |
| [get_Matrix](../graphicelement/get_matrix/)() const | Gets graphic element matrix. The matrix sets when element is created. It changes when **SetPosition()** is called. |
| [get_Name](./get_name/)() | Gets name of the [XForm](../../aspose.pdf/xform/). |
| [get_Operators](../graphicelement/get_operators/)() const | Gets a collection of operators representing the element. |
| [get_Parent](../graphicelement/get_parent/)() const | Gets the current [XFormPlacement](./) in which the element is located. |
| virtual [get_Position](../graphicelement/get_position/)() | Gets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
| [get_Rectangle](./get_rectangle/)() override | Gets the bounding rectangle of the [GraphicElement](../graphicelement/). |
| [get_SourcePage](../graphicelement/get_sourcepage/)() const | Gets the page from which the graphic element is extracted. |
| [get_XForm](./get_xform/)() const | Gets [XForm](../../aspose.pdf/xform/) associated with this [XFormPlacement](./). |
| [Remove](../graphicelement/remove/)() | Removes current element from the page. If there are many elements to remove better use [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](../graphicelement/savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](../graphicelement/savetosvg/)(System::String) | Converts the element into a single SVG image file. |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) override | Sets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
## See Also

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
