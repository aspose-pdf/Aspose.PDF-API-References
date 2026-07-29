---
title: "类 Matrix"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Matrix 类。该类表示变换矩阵"
type: docs
weight: 7060
url: /zh/net/aspose.pdf/matrix/
---
## Matrix class

类表示变换 Matrix。

```csharp
public sealed class Matrix
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 构造函数创建标准 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | 构造函数接受具有以下数组表示的矩阵: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | 构造函数接受具有以下数组表示的矩阵: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | 构造函数接受一个矩阵以创建副本 |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | 使用指定系数初始化变换矩阵。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | 变换矩阵的 A 成员。 |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | 变换矩阵的 B 成员。 |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | 变换矩阵的 C 成员。 |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | 变换矩阵的 D 成员。 |
| [Data](../../aspose.pdf/matrix/data/) { get; } | 获取 Matrix 数据为数组。 |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | 变换矩阵的 E 成员。 |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Matrix 的元素。 |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | 变换矩阵的 F 成员。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | 为给定旋转角度创建矩阵。 |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | 为给定旋转创建矩阵。 |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | 对给定矩阵应用缩放。 |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | 为给定旋转角度创建矩阵。 |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | 在 x 和 y 方向上按指定量平移矩阵。 |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | 将矩阵添加到另一个矩阵。 |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | 比较矩阵与其他对象。 |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | 获取翻转矩阵。 |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | 对象的哈希码。 |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | 将矩阵与另一个矩阵相乘。 |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | 计算逆矩阵。 |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | 使用以下公式对 x 和 y 进行缩放：x1 = A*x + C*y; y1 = B*x + D*y； |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | 返回矩阵的文本表示。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | 使用此矩阵转换点。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | 转换矩形。如果角度不是 90 * N 度，则返回外接矩形。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | 使用此矩阵转换坐标。 |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | 使用以下公式将 x1 和 y1 缩放回并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B)； |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | 使用以下公式将 x1 和 y1 反向转换并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。 |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | 将旋转转换为角度（度） |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


