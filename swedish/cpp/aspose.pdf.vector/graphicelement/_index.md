---
title: "Aspose::Pdf::Vector::GraphicElement class"
linktitle: "GraphicElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::GraphicElement class. Representerar basklass för grafikobjekt på sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.vector/graphicelement/
---
## GraphicElement class


Representerar basklass för grafikobjekt på sidan.

```cpp
class GraphicElement : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av klassen [GraphicElement](./). |
| [get_Matrix](./get_matrix/)() const | Hämtar grafikelementets matris. Matrisen sätts när elementet skapas. Den ändras när **SetPosition()** anropas. |
| [get_Operators](./get_operators/)() const | Hämtar en samling av operatorer som representerar elementet. |
| [get_Parent](./get_parent/)() const | Hämtar den aktuella [XFormPlacement](../xformplacement/) där elementet är placerat. |
| virtual [get_Position](./get_position/)() | Hämtar positionen i det aktuella koordinatrymmet. Om [Parent](../) inte är [null](../) har elementet xForm-koordinatrymd. |
| virtual [get_Rectangle](./get_rectangle/)() | Hämtar den omgivande rektangeln för [GraphicElement](./). |
| [get_SourcePage](./get_sourcepage/)() const | Hämtar sidan som grafikelementet extraheras från. |
| [Remove](./remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](./savetosvg/)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](./savetosvg/)(const System::String\&) | Konverterar elementet till en enda SVG-bildfil. |
| virtual [set_Position](./set_position/)(System::SharedPtr\<Point\>) | Ställer in positionen i det aktuella koordinatrymmet. Om [Parent](../) inte är [null](../) har elementet xForm‑koordinatrymd. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
