---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Matrix. Класс представляет собой матрицу преобразования
type: docs
weight: 6920
url: /ru/net/aspose.pdf/matrix/
---
## Класс Matrix

Класс представляет собой матрицу преобразования.

```csharp
public sealed class Matrix
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [Matrix](matrix/#constructor)() | Конструктор создает стандартную матрицу 1 к 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Конструктор принимает матрицу с следующим представлением массива: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Конструктор принимает матрицу с следующим представлением массива: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Конструктор принимает матрицу для создания копии |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Инициализирует матрицу преобразования с заданными коэффициентами. |

## Свойства

| Название | Описание |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Член матрицы преобразования A. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Член матрицы преобразования B. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Член матрицы преобразования C. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Член матрицы преобразования D. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Получает данные матрицы в виде массива. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Член матрицы преобразования E. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Элементы матрицы. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Член матрицы преобразования F. |

## Методы

| Название | Описание |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Создает матрицу для заданного угла поворота. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Создает матрицу для заданного поворота. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Применяет масштабирование к заданной матрице. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Создает матрицу для заданного угла наклона. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Перемещает матрицу на заданное количество в направлениях x и y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Добавляет матрицу к другой матрице. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Сравнивает матрицу с другим объектом. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Получает матрицу переворота. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Хэш-код для объекта. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Умножает матрицу на другую матрицу. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Вычисляет обратную матрицу. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Возвращает текстовое представление матрицы. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Преобразует точку с помощью этой матрицы. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Преобразует прямоугольник. Если угол не равен 90 * N градусам, то возвращается ограничивающий прямоугольник. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Преобразует координаты с помощью этой матрицы. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Масштабирует обратно x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Преобразует обратно x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Переводит поворот в угол (градусы) |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)