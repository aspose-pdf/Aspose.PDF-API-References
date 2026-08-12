---
title: "Aspose::Pdf::Annotations::PolyAnnotation класс"
linktitle: "PolyAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::PolyAnnotation класс. Абстрактный базовый класс для полигональных аннотаций в C++."
type: docs
weight: 8400
url: /ru/cpp/aspose.pdf.annotations/polyannotation/
---
## PolyAnnotation class


Абстрактный базовый класс для полигональных аннотаций.

```cpp
class PolyAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Обновляет точки в Vertices в соответствии с преобразованием матрицы. |
| [get_EndingStyle](./get_endingstyle/)() | Получает стиль окончания второй линии. |
| [get_Intent](./get_intent/)() | Получает назначение полигональной или полилинейной аннотации. |
| [get_InteriorColor](./get_interiorcolor/)() | Получает внутренний цвет, которым заполняются окончания линий аннотации. |
| [get_Measure](./get_measure/)() | единицы [Measure](../measure/) указаны для этой аннотации. |
| [get_StartingStyle](./get_startingstyle/)() | Получает стиль окончания первой линии. |
| [get_Vertices](./get_vertices/)() | Получает массив точек, представляющих горизонтальные и вертикальные координаты каждой вершины. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Устанавливает стиль окончания второй линии. |
| [set_Intent](./set_intent/)(PolyIntent) | Устанавливает назначение полигональной или полилинейной аннотации. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает внутренний цвет, которым заполняются окончания линий аннотации. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | единицы [Measure](../measure/) указаны для этой аннотации. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Устанавливает стиль окончания первой строки. |
| [set_Vertices](./set_vertices/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Устанавливает массив точек, представляющих горизонтальные и вертикальные координаты каждой вершины. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
