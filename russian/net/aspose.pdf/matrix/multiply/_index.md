---
title: "Matrix.Multiply"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix. Умножает матрицу на другую матрицу"
type: docs
weight: 170
url: /ru/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

Умножает матрицу на другую матрицу.

```csharp
public Matrix Multiply(Matrix other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| другой | Matrix | Матрица‑множитель. |

### Возвращаемое значение

Результат умножения.

## Примеры

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


