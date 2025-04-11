---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Rectangle. Класс представляет прямоугольник
type: docs
weight: 9750
url: /ru/net/aspose.pdf/rectangle/
---
## Класс Прямоугольник

Класс представляет прямоугольник.

```csharp
public sealed class Rectangle : ICloneable
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Конструктор Прямоугольника. |

## Свойства

| Название | Описание |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Пустой прямоугольник |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Инициализирует тривиальный прямоугольник, т.е. прямоугольник с нулевой позицией и размером. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Высота прямоугольника. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Проверяет, является ли прямоугольник пустым. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Проверяет, является ли прямоугольник точкой, т.е. LLX равен URX и LLY равен URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Проверяет, является ли прямоугольник тривиальным, т.е. имеет нулевой размер и позицию. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | X-координата нижнего левого угла. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Y-координата нижнего левого угла. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | X-координата верхнего правого угла. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Y-координата верхнего правого угла. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Ширина прямоугольника. |

## Методы

| Название | Описание |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Инициализирует новый прямоугольник из данного экземпляра System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Инициализирует новый прямоугольник из данного экземпляра System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Пытается разобрать строку и извлечь из нее компоненты прямоугольника llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Возвращает координаты центра прямоугольника. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Клонирует объект Прямоугольника. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Определяет, находится ли данная точка внутри прямоугольника. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Определяет, содержит ли прямоугольник линию, представленную двумя точками. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Определяет, содержится ли данная точка внутри прямоугольника. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Проверяет, равны ли прямоугольники, т.е. имеют ли одинаковую позицию и размеры. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Пересекает два прямоугольника. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Определяет, пересекается ли этот прямоугольник с другим прямоугольником. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Объединяет прямоугольники. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Сдвигает прямоугольник на указанные дельты. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Проверяет, близки ли прямоугольники по размеру, т.е. имеют ли почти одинаковую (в пределах дельты) позицию и размеры. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Поворачивает прямоугольник на указанный угол. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Поворачивает прямоугольник на указанный угол. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Преобразует прямоугольник в массив точек ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Преобразует прямоугольник в экземпляр System.Drawing.Rectangle. Позиции и размеры с плавающей запятой обрезаются. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Получает строковое представление прямоугольника. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)