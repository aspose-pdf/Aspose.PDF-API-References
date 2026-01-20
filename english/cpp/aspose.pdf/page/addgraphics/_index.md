---
title: Aspose::Pdf::Page::AddGraphics method
linktitle: AddGraphics
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page::AddGraphics method. Adds graphics to the page. Works faster than adding elements one by one with GraphicElement::AddOnPage(Page) method in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/page/addgraphics/
---
## Page::AddGraphics method


Adds graphics to the page. Works faster than adding elements one by one with [GraphicElement::AddOnPage(Page)](../) method.

```cpp
void Aspose::Pdf::Page::AddGraphics(System::SharedPtr<Aspose::Pdf::Vector::GraphicElementCollection> elements, System::SharedPtr<Aspose::Pdf::Rectangle> rectangle=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elements | System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\> | Graphics collection. |
| rectangle | System::SharedPtr\<Aspose::Pdf::Rectangle\> | Elements will be added to the page if it's 
GraphicElement::Position


is inside the rectangle area. If rectangle is null, all graphic elements will be added |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicElementCollection](../../../aspose.pdf.vector/graphicelementcollection/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
