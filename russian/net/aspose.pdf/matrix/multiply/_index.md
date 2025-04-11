---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Умножает матрицу на другую матрицу
type: docs
weight: 170
url: /ru/net/aspose.pdf/matrix/multiply/
---
## Метод Matrix.Multiply

Умножает матрицу на другую матрицу.

```csharp
public Matrix Multiply(Matrix other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | Matrix | Матрица-множитель. |

### Возвращаемое значение

Результат умножения.

## Примеры

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)