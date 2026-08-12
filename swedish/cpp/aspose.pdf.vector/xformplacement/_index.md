---
title: "Aspose::Pdf::Vector::XFormPlacement klass"
linktitle: "XFormPlacement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::XFormPlacement klass. Representerar XForm‑placering. Om XForm visas på sidan mer än en gång, kommer alla XformPlacements som är associerade med detta XForm att ha gemensamma grafiska element, men olika grafiska tillstånd i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class


Representerar [XForm](../../aspose.pdf/xform/) placering. Om [XForm](../../aspose.pdf/xform/) visas på sidan mer än en gång, kommer alla XformPlacements som är associerade med detta [XForm](../../aspose.pdf/xform/) att ha gemensamma grafiska element, men olika grafiska tillstånd.

```cpp
class XFormPlacement : public Aspose::Pdf::Vector::GraphicElement
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) override | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [get_Elements](./get_elements/)() const | Hämtar grafiska element i detta [XForm](../../aspose.pdf/xform/). |
| [get_Name](./get_name/)() | Hämtar namn på [XForm](../../aspose.pdf/xform/). |
| [get_Rectangle](./get_rectangle/)() override | Hämtar den begränsande rektangeln för [GraphicElement](../graphicelement/). |
| [get_XForm](./get_xform/)() const | Hämtar [XForm](../../aspose.pdf/xform/) som är associerad med detta [XFormPlacement](./). |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) override | Ställer in positionen i det aktuella koordinatrymmet. Om [Parent](../) inte är [null](../) har elementet xForm‑koordinatrymd. |
## Se även

* Class [GraphicElement](../graphicelement/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
