---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Преобразует обратно x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу x = D  x1 - C  y1 + C  F / A  D - C  B; y = A  y1 - B  x1 + B  E / A  D - C  B.
type: docs
weight: 230
url: /ru/net/aspose.pdf/matrix/untransform/
---
## Метод Matrix.UnTransform

Преобразует обратно x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | Double | Входная координата X |
| y1 | Double | Входная координата Y |
| x | Double& | Выходная координата X |
| y | Double& | Выходная координата Y |

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)