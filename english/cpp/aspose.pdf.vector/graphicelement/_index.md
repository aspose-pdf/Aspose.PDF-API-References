---
title: Aspose::Pdf::Vector::GraphicElement class
linktitle: GraphicElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::GraphicElement class. Represents base class for graphics object on the page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.vector/graphicelement/
---
## GraphicElement class


Represents base class for graphics object on the page.

```cpp
class GraphicElement : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) | Adds current element on the page. If there are many elements to add better use [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [Dispose](./dispose/)() override | Releases all resources used by the [GraphicElement](./) class. |
| [get_Matrix](./get_matrix/)() const | Gets graphic element matrix. The matrix sets when element is created. It changes when **SetPosition()** is called. |
| [get_Operators](./get_operators/)() const | Gets a collection of operators representing the element. |
| [get_Parent](./get_parent/)() const | Gets the current [XFormPlacement](../xformplacement/) in which the element is located. |
| virtual [get_Position](./get_position/)() | Gets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
| virtual [get_Rectangle](./get_rectangle/)() | Gets the bounding rectangle of the [GraphicElement](./). |
| [get_SourcePage](./get_sourcepage/)() const | Gets the page from which the graphic element is extracted. |
| [Remove](./remove/)() | Removes current element from the page. If there are many elements to remove better use [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](./savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](./savetosvg/)(System::String) | Converts the element into a single SVG image file. |
| virtual [set_Position](./set_position/)(System::SharedPtr\<Point\>) | Sets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
