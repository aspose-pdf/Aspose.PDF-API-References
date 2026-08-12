---
title: "Aspose::Pdf::Vector::XFormPlacement class"
linktitle: "XFormPlacement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Vector::XFormPlacement class. Представляет размещение XForm. Если XForm отображается на странице более одного раза, все XFormPlacement, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class


Представляет размещение [XForm](../../aspose.pdf/xform/). Если [XForm](../../aspose.pdf/xform/) отображается на странице более одного раза, все XFormPlacement, связанные с этим [XForm](../../aspose.pdf/xform/), будут иметь общие графические элементы, но разные графические состояния.

```cpp
class XFormPlacement : public Aspose::Pdf::Vector::GraphicElement
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) override | Добавляет текущий элемент на страницу. Если требуется добавить много элементов, лучше использовать [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [get_Elements](./get_elements/)() const | Получает графические элементы внутри этого [XForm](../../aspose.pdf/xform/). |
| [get_Name](./get_name/)() | Получает имя [XForm](../../aspose.pdf/xform/). |
| [get_Rectangle](./get_rectangle/)() override | Получает ограничивающий прямоугольник [GraphicElement](../graphicelement/). |
| [get_XForm](./get_xform/)() const | Получает [XForm](../../aspose.pdf/xform/) , связанный с этим [XFormPlacement](./). |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) override | Устанавливает позицию в текущем пространстве координат. Если [Parent](../) не [null](../), то элемент имеет пространство координат xForm. |
## См. также

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
