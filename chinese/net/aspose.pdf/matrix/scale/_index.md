---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。使用以下公式缩放 x 和 y：x1 = Ax + Cy; y1 = Bx + Dy
type: docs
weight: 190
url: /zh/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

使用以下公式缩放 x 和 y：x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 输入 X 坐标 |
| y | Double | 输入 Y 坐标 |
| x1 | Double& | 输出 X 坐标 |
| y1 | Double& | 输出 Y 坐标 |

### 另请参阅

* 类 [Matrix](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

对给定矩阵应用缩放。

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | Double | X 轴的缩放因子。 |
| sy | Double | Y 轴的缩放因子。 |
| source | Matrix | 要缩放的矩阵。 |

### 返回值

一个新的矩阵，是缩放源矩阵的结果。

### 另请参阅

* 类 [Matrix](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)