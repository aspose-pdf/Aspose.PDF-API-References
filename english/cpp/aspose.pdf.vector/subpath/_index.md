---
title: Aspose::Pdf::Vector::SubPath class
linktitle: SubPath
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::SubPath class. Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.vector/subpath/
---
## SubPath class


Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the [SubPath](./), but visually you only see the text on the page.

```cpp
class SubPath : public Aspose::Pdf::Vector::GraphicElement
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddOnPage](../graphicelement/addonpage/)(System::SharedPtr\<Page\>) | Adds current element on the page. If there are many elements to add better use [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [Dispose](../graphicelement/dispose/)() override | Releases all resources used by the [GraphicElement](../graphicelement/) class. |
| [get_Matrix](../graphicelement/get_matrix/)() const | Gets graphic element matrix. The matrix sets when element is created. It changes when **SetPosition()** is called. |
| [get_Operators](../graphicelement/get_operators/)() const | Gets a collection of operators representing the element. |
| [get_Parent](../graphicelement/get_parent/)() const | Gets the current [XFormPlacement](../xformplacement/) in which the element is located. |
| virtual [get_Position](../graphicelement/get_position/)() | Gets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
| [get_Rectangle](./get_rectangle/)() override | Gets the bounding rectangle of the [GraphicElement](../graphicelement/). |
| [get_SourcePage](../graphicelement/get_sourcepage/)() const | Gets the page from which the graphic element is extracted. |
| [Remove](../graphicelement/remove/)() | Removes current element from the page. If there are many elements to remove better use [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](../graphicelement/savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](../graphicelement/savetosvg/)(System::String) | Converts the element into a single SVG image file. |
| virtual [set_Position](../graphicelement/set_position/)(System::SharedPtr\<Point\>) | Sets the position in the current coordinate space. If [Parent](../) is not [null](../) then the element have xForm coordinate space. |
## See Also

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
