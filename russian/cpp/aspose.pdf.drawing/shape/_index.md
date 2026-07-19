---
title: "Класс Aspose::Pdf::Drawing::Shape"
linktitle: "Фигура"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Drawing::Shape. Представляет фигуру — базовый графический объект в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.pdf.drawing/shape/
---
## Shape class


Представляет форму — базовый графический объект.

```cpp
class Shape : public Aspose::Pdf::IBoundsCheckableItem
```

## Методы

| Метод | Описание |
| --- | --- |
| [CheckBounds](./checkbounds/)(double, double) override | Проверяет, помещается ли элемент в заданные размеры контейнера (включительно). |
| [get_GraphInfo](./get_graphinfo/)() const | Получает объект [GraphInfo](../../aspose.pdf/graphinfo/), который указывает информацию о графе, такую как цвет, ширина линии и т.д. |
| [get_Text](./get_text/)() const | Получает текст для фигуры. |
| [set_GraphInfo](./set_graphinfo/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Устанавливает объект [GraphInfo](../../aspose.pdf/graphinfo/), который указывает информацию о графе, такую как цвет, ширина линии и т.д. |
| [set_Text](./set_text/)(const System::SharedPtr\<Text::TextFragment\>\&) | Устанавливает текст для фигуры. |
| [Shape](./shape/)() |  |
## См. также

* Class [IBoundsCheckableItem](../../aspose.pdf/iboundscheckableitem/)
* Namespace [Aspose::Pdf::Drawing](../)
* Library [Aspose.PDF for C++](../../)
