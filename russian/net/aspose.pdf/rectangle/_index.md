---
title: "Класс Rectangle"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Rectangle. Класс представляет прямоугольник."
type: docs
weight: 9900
url: /ru/net/aspose.pdf/rectangle/
---
## Rectangle class

Класс представляет прямоугольник.

```csharp
public sealed class Rectangle : ICloneable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Конструктор Rectangle. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Пустой Rectangle |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Инициализирует тривиальный Rectangle, то есть Rectangle с нулевыми координатами и размером. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Высота прямоугольника. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Проверяет, пустой ли прямоугольник. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Проверяет, является ли прямоугольник точкой, т.е. LLX равно URX и LLY равно URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Проверяет, является ли прямоугольник тривиальным, т.е. имеет нулевой размер и положение. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Координата X нижнего‑левого угла. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Координата Y нижнего‑левого угла. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Координата X верхнего‑правого угла. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Координата Y верхнего‑правого угла. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Ширина прямоугольника. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Инициализирует новый прямоугольник из заданного экземпляра System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Инициализирует новый прямоугольник из заданного экземпляра System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Пытается разобрать строку и извлечь из неё компоненты прямоугольника llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Возвращает координаты центра прямоугольника. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Клонирует объект Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Определяет, находится ли заданная точка внутри прямоугольника. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Определяет, содержит ли прямоугольник линию, представленную двумя точками. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Определяет, содержится ли заданная точка в прямоугольнике. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Проверяет, равны ли прямоугольники, т.е. имеют одинаковое положение и размеры. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Пересекает прямоугольники. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Определяет, пересекается ли этот прямоугольник с другим прямоугольником. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Объединяет прямоугольники. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Смещает прямоугольник на указанные дельты. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Проверяет, почти ли равны прямоугольники, т.е. имеют почти одинаковое (с учётом дельты) положение и размеры. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Поворачивает прямоугольник на указанный угол. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Поворачивает прямоугольник на указанный угол. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Преобразует прямоугольник в массив точек ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Преобразует прямоугольник в экземпляр System.Drawing.Rectangle. Позиции и размеры с плавающей точкой усекаются. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Получает строковое представление прямоугольника. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


