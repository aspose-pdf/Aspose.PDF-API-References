---
title: "Aspose::Pdf::Vector::GraphicElement класс"
linktitle: "GraphicElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Vector::GraphicElement класс. Представляет базовый класс для графических объектов на странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.vector/graphicelement/
---
## GraphicElement class


Представляет базовый класс для графического объекта на странице.

```cpp
class GraphicElement : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AddOnPage](./addonpage/)(System::SharedPtr\<Page\>) | Добавляет текущий элемент на страницу. Если требуется добавить много элементов, лучше использовать [Page::AddGraphics(GraphicElementCollection, Rectangle)](../). |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые классом [GraphicElement](./). |
| [get_Matrix](./get_matrix/)() const | Получает матрицу графического элемента. Матрица устанавливается при создании элемента. Она изменяется, когда вызывается **SetPosition()**. |
| [get_Operators](./get_operators/)() const | Получает коллекцию операторов, представляющих элемент. |
| [get_Parent](./get_parent/)() const | Получает текущий [XFormPlacement](../xformplacement/), в котором расположен элемент. |
| virtual [get_Position](./get_position/)() | Получает позицию в текущем координатном пространстве. Если [Parent](../) не является [null](../), то элемент имеет координатное пространство xForm. |
| virtual [get_Rectangle](./get_rectangle/)() | Получает ограничивающий прямоугольник [GraphicElement](./). |
| [get_SourcePage](./get_sourcepage/)() const | Получает страницу, из которой извлекается графический элемент. |
| [Remove](./remove/)() | Удаляет текущий элемент со страницы. Если требуется удалить много элементов, лучше использовать [Page::DeleteGraphics(GraphicElementCollection)](../). |
| [SaveToSvg](./savetosvg/)() | Преобразует элемент в одно SVG‑изображение. |
| [SaveToSvg](./savetosvg/)(const System::String\&) | Преобразует элемент в один файл SVG‑изображения. |
| virtual [set_Position](./set_position/)(System::SharedPtr\<Point\>) | Устанавливает позицию в текущем пространстве координат. Если [Parent](../) не [null](../), то элемент имеет пространство координат xForm. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
