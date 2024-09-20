---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Matrix method. Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B
type: docs
weight: 230
url: /net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | Double | Input X coordinate |
| y1 | Double | Input Y coordinate |
| x | Double& | Output X coordinate |
| y | Double& | Output Y coordinate |

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


