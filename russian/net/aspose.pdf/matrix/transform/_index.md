---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Метод Matrix. Преобразует точку с использованием этой матрицы
type: docs
weight: 210
url: /ru/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Преобразует точку с использованием этой матрицы.

```csharp
public Point Transform(Point p)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Point | Точка, которая будет преобразована. |

### Возвращаемое значение

Результат преобразования.

## Примеры

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### См. также

* класс [Point](../../point/)
* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Преобразует координаты с использованием этой матрицы.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | X координата. |
| y | Double | Y координата. |
| x1 | Double& | Преобразованная X координата. |
| y1 | Double& | Преобразованная Y координата. |

## Примеры

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Преобразует прямоугольник. Если угол не равен 90 * N градусов, то возвращается ограничивающий прямоугольник.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник, который будет преобразован. |

### Возвращаемое значение

Преобразованный прямоугольник.

## Примеры

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)