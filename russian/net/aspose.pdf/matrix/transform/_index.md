---
title: "Matrix.Transform"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix. Преобразует точку, используя эту матрицу"
type: docs
weight: 210
url: /ru/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Преобразует точку, используя эту матрицу.

```csharp
public Point Transform(Point p)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Точка | Точка, которая будет преобразована. |

### Возвращаемое значение

Результат преобразования.

## Примеры

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### См. также

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Преобразует координаты, используя эту матрицу.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Координата X. |
| y | Double | Координата Y. |
| x1 | Double& | Преобразованная координата X. |
| y1 | Double& | Преобразованная координата Y. |

## Примеры

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Преобразует прямоугольник. Если угол не равен 90 * N градусов, возвращается ограничивающий прямоугольник.

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

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


