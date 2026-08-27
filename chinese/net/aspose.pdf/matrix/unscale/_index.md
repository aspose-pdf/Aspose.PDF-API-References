---
title: "Matrix.UnScale"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix 方法。使用以下公式将 x1 和 y1 反向缩放并返回矩阵变换前的 x 和 y：x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B"
type: docs
weight: 220
url: /zh/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale method

使用以下公式将 x1 和 y1 缩放回并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B)；

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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


