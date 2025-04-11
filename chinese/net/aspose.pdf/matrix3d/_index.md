---
title: Class Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix3D 类。类表示变换矩阵
type: docs
weight: 6930
url: /zh/net/aspose.pdf/matrix3d/
---
## Matrix3D class

类表示变换矩阵。

```csharp
public sealed class Matrix3D
```

## Constructors

| Name | Description |
| --- | --- |
| [Matrix3D](matrix3d/#constructor)() | 构造函数创建标准的 1 到 1 矩阵: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](matrix3d/#constructor_3)(double[]) | 构造函数接受具有以下数组表示的矩阵: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](matrix3d/#constructor_1)(Matrix3D) | 构造函数接受一个矩阵以创建副本 |
| [Matrix3D](matrix3d/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double) | 使用指定系数初始化变换矩阵。 |

## Properties

| Name | Description |
| --- | --- |
| [A](../../aspose.pdf/matrix3d/a/) { get; set; } | 变换矩阵的 A 成员。 |
| [B](../../aspose.pdf/matrix3d/b/) { get; set; } | 变换矩阵的 B 成员。 |
| [C](../../aspose.pdf/matrix3d/c/) { get; set; } | 变换矩阵的 C 成员。 |
| [D](../../aspose.pdf/matrix3d/d/) { get; set; } | 变换矩阵的 D 成员。 |
| [E](../../aspose.pdf/matrix3d/e/) { get; set; } | 变换矩阵的 E 成员。 |
| [F](../../aspose.pdf/matrix3d/f/) { get; set; } | 变换矩阵的 F 成员。 |
| [G](../../aspose.pdf/matrix3d/g/) { get; set; } | 变换矩阵的 G 成员。 |
| [H](../../aspose.pdf/matrix3d/h/) { get; set; } | 变换矩阵的 H 成员。 |
| [I](../../aspose.pdf/matrix3d/i/) { get; set; } | 变换矩阵的 I 成员。 |
| [Tx](../../aspose.pdf/matrix3d/tx/) { get; set; } | 变换矩阵的 Tx 成员。 |
| [Ty](../../aspose.pdf/matrix3d/ty/) { get; set; } | 变换矩阵的 Ty 成员。 |
| [Tz](../../aspose.pdf/matrix3d/tz/) { get; set; } | 变换矩阵的 Tz 成员。 |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/matrix3d/add/)(Matrix3D) | 将矩阵添加到其他矩阵。 |
| override [Equals](../../aspose.pdf/matrix3d/equals/)(object) | 将矩阵与其他对象进行比较。 |
| override [GetHashCode](../../aspose.pdf/matrix3d/gethashcode/)() | 对象的哈希码。 |
| override [ToString](../../aspose.pdf/matrix3d/tostring/)() | 返回矩阵的文本表示。 |
| static [GetAngle](../../aspose.pdf/matrix3d/getangle/)(Rotation) | 将旋转转换为角度（度） |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)