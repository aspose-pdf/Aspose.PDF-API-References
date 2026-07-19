---
title: "Aspose::Pdf::Page::AddGraphics метод"
linktitle: "AddGraphics"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Page::AddGraphics метод. Добавляет графику на страницу. Работает быстрее, чем добавление элементов по одному с помощью метода GraphicElement::AddOnPage(Page) в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/page/addgraphics/
---
## Page::AddGraphics method


Добавляет графику на страницу. Работает быстрее, чем добавление элементов по одному с помощью метода [GraphicElement::AddOnPage(Page)](../).

```cpp
void Aspose::Pdf::Page::AddGraphics(const System::SharedPtr<Aspose::Pdf::Vector::GraphicElementCollection> &elements, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элементы | const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\& | Коллекция графики. |
|  | прямоугольник | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Элементы будут добавлены на страницу, если она |
GraphicElement::Position


находится внутри области прямоугольника. Если прямоугольник равен null, все графические элементы будут добавлены |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicElementCollection](../../../aspose.pdf.vector/graphicelementcollection/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
