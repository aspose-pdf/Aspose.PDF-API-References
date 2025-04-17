---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Возвращает x и y до преобразования матрицы, масштабируя обратно x1 и y1 с использованием следующей формулы x = D * x1 - C * y1 / A * D - C * B; y = A * y1 - B * x1 / A * D - C * B;
type: docs
weight: 220
url: /ru/net/aspose.pdf/matrix/unscale/
---
## Метод Matrix.UnScale

Возвращает x и y до преобразования матрицы, масштабируя обратно x1 и y1 с использованием следующей формулы: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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