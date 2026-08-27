---
title: "Matrix.UnTransform"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix 方法。使用以下公式将 x1 和 y1 反向变换并返回矩阵变换前的 x 和 y：x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /zh/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

使用以下公式将 x1 和 y1 反向转换并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | Double | 输入 X 坐标 |
| y1 | Double | 输入 Y 坐标 |
| x | Double& | 输出 X 坐标 |
| y | Double& | 输出 Y 坐标 |

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


