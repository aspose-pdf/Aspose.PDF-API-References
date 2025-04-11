---
title: Matrix.Skew
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Создает матрицу для заданного угла поворота
type: docs
weight: 30
url: /ru/net/aspose.pdf/matrix/skew/
---
## Метод Matrix.Skew

Создает матрицу для заданного угла поворота.

```csharp
public static Matrix Skew(double alpha, double beta)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Double | Угол наклона по оси x в радианах. |
| beta | Double | Угол наклона по оси y в радианах. |

### Возвращаемое значение

Матрица преобразования.

## Примеры

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)