---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。使用以下公式将 x1 和 y1 转换回并返回矩阵变换之前的 x 和 y：x = Dx1 - Cy1 + CF / AD - CB, y = Ay1 - Bx1 + BE / AD - CB。
type: docs
weight: 230
url: /zh/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform 方法

使用以下公式将 x1 和 y1 转换回并返回矩阵变换之前的 x 和 y：x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。

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

* 类 [Matrix](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)