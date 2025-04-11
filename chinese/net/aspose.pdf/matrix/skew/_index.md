---
title: Matrix.Skew
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。为给定的旋转角度创建矩阵
type: docs
weight: 30
url: /zh/net/aspose.pdf/matrix/skew/
---
## Matrix.Skew 方法

为给定的旋转角度创建矩阵。

```csharp
public static Matrix Skew(double alpha, double beta)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Double | x 方向的倾斜角度（弧度）。 |
| beta | Double | y 方向的倾斜角度（弧度）。 |

### 返回值

变换矩阵。

## 示例

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### 另请参阅

* 类 [Matrix](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)