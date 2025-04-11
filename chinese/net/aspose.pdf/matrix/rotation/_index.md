---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。为给定的旋转角度创建矩阵
type: docs
weight: 20
url: /zh/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

为给定的旋转角度创建矩阵。

```csharp
public static Matrix Rotation(double alpha)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Double | 以弧度表示的旋转角度。 |

### 返回值

变换矩阵。

## 示例

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

为给定的旋转创建矩阵。

```csharp
public static Matrix Rotation(Rotation rotation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotation | Rotation | 旋转。有效值为：None, on90, on180, on270 |

### 返回值

带有旋转的矩阵。

### 另请参见

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)