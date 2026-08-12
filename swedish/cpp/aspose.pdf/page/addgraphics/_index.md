---
title: "Aspose::Pdf::Page::AddGraphics metod"
linktitle: "AddGraphics"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Page::AddGraphics metod. Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med GraphicElement::AddOnPage(Page) metod i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/page/addgraphics/
---
## Page::AddGraphics method


Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med metoden [GraphicElement::AddOnPage(Page)](../).

```cpp
void Aspose::Pdf::Page::AddGraphics(const System::SharedPtr<Aspose::Pdf::Vector::GraphicElementCollection> &elements, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\& | Grafiksamling. |
|  | rectangle | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Element kommer att läggas till på sidan om det är |
GraphicElement::Position


är inom rektangelområdet. Om rektangeln är null, kommer alla grafiska element att läggas till |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicElementCollection](../../../aspose.pdf.vector/graphicelementcollection/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
