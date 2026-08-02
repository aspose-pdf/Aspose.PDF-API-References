---
title: "Класс Matrix"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Matrix. Класс представляет матрицу преобразования"
type: docs
weight: 7060
url: /ru/net/aspose.pdf/matrix/
---
## Matrix class

Класс представляет матрицу преобразования.

```csharp
public sealed class Matrix
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Matrix](matrix/#constructor)() | Конструктор создаёт стандартную матрицу 1 к 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Конструктор принимает матрицу для создания копии |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Инициализирует матрицу преобразования с указанными коэффициентами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Элемент A матрицы преобразования. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Элемент B матрицы преобразования. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Элемент C матрицы преобразования. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Элемент D матрицы преобразования. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Получает данные Matrix в виде массива. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Элемент E матрицы преобразования. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Элементы матрицы. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Элемент F матрицы преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Создаёт матрицу для заданного угла вращения. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Создает матрицу для заданного вращения. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Применяет масштабирование к заданной матрице. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Создаёт матрицу для заданного угла вращения. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Перемещает матрицу на указанную величину по осям x и y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Добавляет матрицу к другой матрице. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Сравнивает матрицу с другим объектом. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Получает матрицу отражения. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Хеш-код объекта. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Умножает матрицу на другую матрицу. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Вычисляет обратную матрицу. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Возвращает текстовое представление матрицы. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Преобразует точку, используя эту матрицу. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Преобразует прямоугольник. Если угол не равен 90 * N градусов, возвращается ограничивающий прямоугольник. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Преобразует координаты, используя эту матрицу. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Обратно масштабирует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Обратно преобразует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Преобразует вращение в угол (градусы) |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


