---
title: "Aspose::Pdf::Drawing::Graph class"
linktitle: "Граф"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Drawing::Graph. Представляет граф — абзац генератора графики в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.drawing/graph/
---
## Graph class


Представляет граф — абзац генератора графики.

```cpp
class Graph : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонировать граф. |
| [get_Border](./get_border/)() const | Получает границу. |
| [get_GraphInfo](./get_graphinfo/)() const | Получает объект [GraphInfo](../../aspose.pdf/graphinfo/), который указывает информацию о графе, такую как цвет, ширина линии и т.д. |
| [get_Height](./get_height/)() const | Получает значение типа float, указывающее высоту графа. Единица измерения — пункт. |
| [get_IsChangePosition](./get_ischangeposition/)() const | Получает изменение текущей позиции после обработки абзаца. (по умолчанию true) |
| [get_Left](./get_left/)() const | Получает левую координату таблицы. |
| [get_Shapes](./get_shapes/)() const | Получает коллекцию [Shapes](../), которая указывает все фигуры в графе. |
| [get_Title](./get_title/)() const | Получает строковое значение, указывающее заголовок графа. |
| [get_Top](./get_top/)() const | Получает верхнюю координату таблицы. |
| [get_Width](./get_width/)() const | Получает значение типа float, указывающее ширину графа. Единица измерения — пункт. |
| [Graph](./graph/)(double, double) | Инициализирует новый экземпляр класса [Graph](./). |
| [Graph](./graph/)(float, float) | Инициализирует новый экземпляр класса [Graph](./). |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает границу. |
| [set_GraphInfo](./set_graphinfo/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Устанавливает объект [GraphInfo](../../aspose.pdf/graphinfo/), который указывает информацию о графе, такую как цвет, ширина линии и т.д. |
| [set_Height](./set_height/)(double) | Устанавливает значение типа float, указывающее высоту графа. Единица измерения — пункт. |
| [set_IsChangePosition](./set_ischangeposition/)(bool) | Устанавливает изменение текущей позиции после обработки абзаца. (по умолчанию true) |
| [set_Left](./set_left/)(double) | Устанавливает левую координату таблицы. |
| [set_Shapes](./set_shapes/)(const System::SharedPtr\<BoundsCheckableList\<System::SharedPtr\<Shape\>\>\>\&) | Устанавливает коллекцию [Shapes](../), которая указывает все фигуры в графе. |
| [set_Title](./set_title/)(const System::SharedPtr\<Text::TextFragment\>\&) | Устанавливает строковое значение, указывающее заголовок графа. |
| [set_Top](./set_top/)(double) | Устанавливает верхнюю координату таблицы. |
| [set_Width](./set_width/)(double) | Устанавливает значение типа float, указывающее ширину графа. Единица измерения — пункт. |
## См. также

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Drawing](../)
* Library [Aspose.PDF for C++](../../)
