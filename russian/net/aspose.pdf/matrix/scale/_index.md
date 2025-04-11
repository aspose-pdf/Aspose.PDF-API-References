---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Масштабирует x и y с помощью матрицы, используя следующую формулу x1 = A*x + C*y; y1 = B*x + D*y
type: docs
weight: 190
url: /ru/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Входная координата X |
| y | Double | Входная координата Y |
| x1 | Double& | Выходная координата X |
| y1 | Double& | Выходная координата Y |

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Применяет масштабирование к данной матрице.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | Double | Коэффициент масштабирования для оси X. |
| sy | Double | Коэффициент масштабирования для оси Y. |
| source | Matrix | Матрица для масштабирования. |

### Возвращаемое значение

Новая матрица, которая является результатом масштабирования исходной матрицы.

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)