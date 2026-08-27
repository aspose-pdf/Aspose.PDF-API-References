---
title: "Matrix.Scale"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix. Масштабирует x и y с помощью матрицы, используя следующую формулу x1  Ax  Cy y1  Bx  Dy"
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

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Применяет масштабирование к заданной матрице.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | Double | Коэффициент масштабирования по оси X. |
| sy | Double | Коэффициент масштабирования по оси Y. |
| источник | Matrix | Матрица для масштабирования. |

### Возвращаемое значение

Новая матрица, полученная в результате масштабирования исходной матрицы.

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


