---
title: "Класс Aspose::Pdf::Rectangle"
linktitle: "Rectangle"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Rectangle. Класс представляет прямоугольник в C++."
type: docs
weight: 16300
url: /ru/cpp/aspose.pdf/rectangle/
---
## Rectangle class


Класс представляет прямоугольник.

```cpp
class Rectangle : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Center](./center/)() | Возвращает координаты центра прямоугольника. |
| [Clone](./clone/)() override | Клонирует объект [Rectangle](./). |
| [Contains](./contains/)(const System::SharedPtr\<Point\>\&, bool) | Определяет, находится ли заданная точка внутри прямоугольника. |
| [ContainsLine](./containsline/)(double, double, double, double) | Определяет, содержит ли прямоугольник линию, представленную двумя точками. |
| [ContainsPoint](./containspoint/)(double, double) | Определяет, содержится ли заданная точка в прямоугольнике. |
| [Equals](./equals/)(const System::SharedPtr\<Rectangle\>\&) | Проверяет, равны ли прямоугольники, т.е. имеют одинаковое положение и размеры. |
| static [FromRect](./fromrect/)(System::Drawing::Rectangle) | Инициализирует новый прямоугольник из заданного экземпляра [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [FromRect](./fromrect/)(System::Drawing::RectangleF) | Инициализирует новый прямоугольник из заданного экземпляра [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [get_Empty](./get_empty/)() | Пустой прямоугольник. |
| [get_Height](./get_height/)() | Высота прямоугольника. |
| [get_IsEmpty](./get_isempty/)() const | Проверяет, пустой ли прямоугольник. |
| [get_IsPoint](./get_ispoint/)() | Проверяет, является ли прямоугольник точкой, т.е. LLX равен URX и LLY равен URY. |
| [get_IsTrivial](./get_istrivial/)() | Проверяет, является ли прямоугольник тривиальным, т.е. имеет нулевой размер и положение. |
| [get_LLX](./get_llx/)() const | X-координата нижнего левого угла. |
| [get_LLY](./get_lly/)() const | Y-координата нижнего левого угла. |
| static [get_Trivial](./get_trivial/)() | Инициализирует тривиальный прямоугольник, т.е. прямоугольник с нулевым положением и размером. |
| [get_URX](./get_urx/)() const | X-координата верхнего правого угла. |
| [get_URY](./get_ury/)() const | Y-координата верхнего правого угла. |
| [get_Width](./get_width/)() | Ширина прямоугольника. |
| [Intersect](./intersect/)(const System::SharedPtr\<Rectangle\>\&) | Пересекает два прямоугольника. |
| [IsIntersect](./isintersect/)(const System::SharedPtr\<Rectangle\>\&) | Определяет, пересекается ли этот прямоугольник с другим прямоугольником. |
| [Join](./join/)(const System::SharedPtr\<Rectangle\>\&) | Объединяет прямоугольники. |
| [MoveBy](./moveby/)(double, double) | Смещает прямоугольник на указанные дельты. |
| [NearEquals](./nearequals/)(const System::SharedPtr\<Rectangle\>\&, double) | Проверяет, почти ли равны прямоугольники, т.е. имеют почти одинаковое (с учётом дельты) положение и размеры. |
| static [Parse](./parse/)(const System::String\&) | Пытается разобрать строку и извлечь из неё компоненты прямоугольника llx, lly, urx, ury. |
| [Rectangle](./rectangle/)(double, double, double, double, bool) | Конструктор [Rectangle](./). |
| [Rotate](./rotate/)(Rotation) | Повернуть прямоугольник на указанный угол. |
| [Rotate](./rotate/)(int32_t) | Повернуть прямоугольник на указанный угол. |
| [set_LLX](./set_llx/)(double) | X-координата нижнего левого угла. |
| [set_LLY](./set_lly/)(double) | Y-координата нижнего левого угла. |
| [set_URX](./set_urx/)(double) | X-координата верхнего правого угла. |
| [set_URY](./set_ury/)(double) | Y-координата верхнего правого угла. |
| [ToPoints](./topoints/)() | Преобразует прямоугольник в массив точек ("QuadPoints"). |
| [ToRect](./torect/)() | Преобразует прямоугольник в экземпляр [System.Drawing.Rectangle](../../system.drawing/rectangle/). Позиции и размеры с плавающей точкой усекаются. |
| [ToString](./tostring/)() const override | Получает строковое представление прямоугольника. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
